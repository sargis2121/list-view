<template>
  <div id="app">
    <TodoList />
  </div>
</template>

<script>
import TodoList from "./components/addText.vue";

export default {
  name: "App",
  components: {
    TodoList,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
body {
  background-color: lightblue;
}
</style>
