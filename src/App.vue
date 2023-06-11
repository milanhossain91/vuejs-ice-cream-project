<template>
  <div>
    <header>
      <div class="container" id="header">
        <div>
          <img class="logo" src="images/logo.svg" alt="Logo" />
        </div>
        <div class="textRight">
          <img src="images/vue.svg" alt="Vue.js" class="vueLogo" />
          <strong>Vue.js</strong>
        </div>
      </div>
    </header>

    <HelloWorld />

    <footer>
      <div class="container" id="footer">
        <div>Copyright &copy;2020.</div>
        <div class="textRight">
          Built with <span class="red">&hearts;</span> by
          <a href="https://encodebase.com" target="_blank">Encoder Base</a>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';

export default {
  components: {
    HelloWorld,
  },
};
</script>

<style scoped>
/* Add your CSS styles here */
</style>
