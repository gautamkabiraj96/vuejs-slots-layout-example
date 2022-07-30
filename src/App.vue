<template>
  <div id="app">
    <layout>
      <template v-slot:header>
        <h1>Header</h1>
      </template>
      <template v-slot:default>
        <h2>Some content</h2>
        <p>Some paragraph</p>
      </template>
      <template v-slot:footer>
        <p>Footer</p>
      </template>
    </layout>
  </div>
</template>

<script>
import Layout from "./Layout";
export default {
  name: "App",
  components: {
    Layout,
  },
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

* {
  margin: 0;
  padding: 0;
}

.np-credits {
  font-size: 12px;
  margin-top: 12px;
  color: #4b4b4b;
}
</style>