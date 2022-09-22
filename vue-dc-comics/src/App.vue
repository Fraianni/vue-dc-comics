<template>
  <div id="app">
    <headerComponent/>
    <contentComponent/>
    <footerComponent/>
  </div>
</template>

<script>
import headerComponent from './components/headerComponent.vue'
import contentComponent from './components/contentComponent.vue'
import footerComponent from './components/footerComponent.vue'


export default {
  name: 'App',
  components: {
    headerComponent,
    contentComponent,
    footerComponent
}
}

</script>

<style>
  * {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

}
</style>
