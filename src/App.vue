<!-- src/App.vue -->


<script>
import Header from './components/Header.vue';

export default {
  name: 'App',
  components: {
    Header,
  },
};
</script>


<template>
  <div id="app">
    <Header />
    <!-- Other components and router-view here -->
  </div>
</template>

<style>
/* Add global styles here */
body {
  font-family: 'Arial', sans-serif;
  margin: 0;
  padding: 0;
}
</style>
