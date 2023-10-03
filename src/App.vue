<script>
import todolist from './components/todolist.vue'
import counter from './components/counter.vue'

export default{
  data(){
     return {
      tasks:["taks1", "taks2", "taks3"]
     }
  },
  components:{
    todolist,
    counter
  },
}
</script>

<template>
  <div>
    <todolist :tasks="tasks"></todolist>
    <div>
      <counter/>
    </div>
  </div>
</template>

<style>

</style>
