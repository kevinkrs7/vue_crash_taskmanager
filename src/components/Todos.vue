
<template>
    <div>
        <div v-bind:key="todo.id" v-for="todo in todos">
            <TodoItem v-bind:todo ="todo">
        </div>
    </div>    
</template>

<script>
export default {
    name: "Todos",
    components:{ 
        TodoItem
    },
    props: ["todos"]
}
</script>

<!-- scoped means, that css attributes will apply to elements of the current components only -->
<style scoped>  

</style>