<template>
  <div id="app">
    <LintedComponent />
    <NotLintedComponent />
  </div>
</template>

<script>
import * as components from './components'

export default {
  name: 'app',
  components
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
