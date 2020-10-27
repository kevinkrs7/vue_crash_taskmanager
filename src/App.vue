<template>
  <div id="app">
    
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
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
