<template>
  <div id="app">
  <TodoList
     v-bind:todos="todos"
  />
  </div>
</template>

<script>

import TodoList from '@/components/TodoList'
export default {
  name: 'App',
  data() {
    return{
       todos: [
         {id: 1, title: 'New folder 1', completed: false},
         {id: 2, title: 'New folder 2', completed: false},
         {id: 3, title: 'New folder 3', completed: false},
         {id: 4, title: 'New folder 4', completed: false},
         {id: 5, title: 'New folder 5', completed: false},
         {id: 6, title: 'New folder 6', completed: false},
         {id: 7, title: 'New folder 7', completed: false},
         {id: 8, title: 'New folder 8', completed: false},
         {id: 9, title: 'New folder 9', completed: false},
         {id: 10, title: 'New folder 10', completed: false},
         {id: 11, title: 'New folder 11', completed: false},
         {id: 12, title: 'New folder 12', completed: false},
         {id: 13, title: 'New folder 13', completed: false},
         {id: 14, title: 'New folder 14', completed: false},
         {id: 15, title: 'New folder 15', completed: false},
         {id: 16, title: 'New folder 16', completed: false},
         {id: 17, title: 'New folder 17', completed: false},
         {id: 18, title: 'New folder 18', completed: false}
       ]
    }
  },
  components: {
    TodoList
  }
}
</script>

<style>
#app {
  font-family: "Open Sans", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #232323;
  text-decoration: none;
  margin-top: 60px;
  font-size: 20px;
  font-style: normal;


}
</style>
