<template>
  <div id="app">
    <Todos v-bind:todos="todos" />
  </div>
</template>

<script>
import Todos from './components/Todos.vue';

export default {
  name: 'App',
  components: {
    Todos
  },
   data() {
    return{
      todos: [
      { 
        id: 1, 
        title: "Todo one", 
        complete: false
      }, 
      { 
        id: 2, 
        title: "Todo two", 
        complete: false
      },
      { 
        id: 3, 
        title: "Todo three", 
        complete: false
      }
      ]
    }
  }
  
}
</script>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  
  }
 body  {
    font-family: Arial, Helvetica, sans-serif;
  }
</style>
