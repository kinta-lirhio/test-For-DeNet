<template>
       <li>
         <span v-bind:class="{done: todo.completed}">

                <strong>{{todo.id}}</strong>
                {{todo.title}}
         </span>

       </li>
</template>

<script>
    export default {
        props: {
            todo: {
              type: Object,
                required: true
            }
        }
    }
</script>
<style scoped>
   li {
     background-color: rgba(172, 173, 181, 1);
     width: 104px;
     height: 75px;
     padding: .5rem 2rem;
     margin-bottom: 1rem;
      }
    .done {
        text-decoration: line-through;
     }
    input {
        margin-right: 1rem;
     }
</style>