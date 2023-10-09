<template lang="">
    <div class="container">
        <h1>using computed setters</h1>
        <input type="number" v-model="incrementOne">
        <h3>Get input: {{ incrementOne}}</h3>

    </div>
</template>
<script>
    export default{
        data(){
            return {
                count: -1,
            }

        },
        computed: {
            incrementOne: {
                //getter
                get(){
                    return this.count + 1
                },
                //setter
                set(val){
                    this.count = val -1

                },

            },

        },

    }

</script>