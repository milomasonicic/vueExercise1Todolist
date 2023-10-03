<script>

export default{
    data(){
        return{
            count:0
        }
    }, 
    methods:{
        increase(){
            this.count++
        },
        decrease(){
            this.count--
        }        
    }
}

</script>

<template>

    <h1>{{ count }}</h1>
    <button @click="increase">+</button>
    <button @click="decrease">-</button>
</template>

<style>

</style>