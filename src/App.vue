<template>
  <div id="app">
      <div>Hello {{name}}</div>
      <input type="text" v-model="name">
  </div>
</template>

<script>
export default {
    data() {
        return {
            name: 'World'
        }
    },
    
}
</script>

<style>

</style>
