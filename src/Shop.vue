<template>
  <div id="shop">
    <Menu />
  </div>
</template>

<script>
import Menu from './components/Menu.vue'

export default {
  name: 'shop',
  components: {
    Menu
  }
}
</script>

<style lang="scss">
@import 'styles/main.scss';

#shop {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
