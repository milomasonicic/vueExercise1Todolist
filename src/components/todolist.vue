<template>
    <h1>To do list:</h1>

    <ul>
        <li v-for=" (task, index) in tasks" :key="index">{{ task }}</li>
        
    </ul>
</template>

<script>

export default{
    props:{
        tasks:{
            type: Array
        }
    }
}

</script>

<style>

</style>