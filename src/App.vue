<template>
  <div class="content">
    <Header />
    <Divider text="About" />
    <About />
  </div>
</template>

<script>
import About from './components/About.vue';
import Divider from './components/Divider.vue';
import Header from './components/Header.vue';

export default {
  name: 'App',
  components: {
    About,
    Divider,
    Header,
  },
};
</script>

<style lang="scss">
#app {
  color: white;
  display: flex;
  font-family: 'Roboto', sans-serif;
  justify-content: center;
  margin: 0;
  text-align: center;
}
.content {
  max-width: 1080px;
}
body {
  background-color: $background-color;
}
</style>
