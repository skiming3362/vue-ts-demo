<template>
  <div id="app">
      <div>Hello {{name}}</div>
      <div>{{test}}</div>
      <input type="text" v-model="name">
  </div>
</template>

<script lang="ts">
export default {
    data() {
        return {
            name: 'World',
            test: 'asd444'
        }
    },
    methods: {
        foo(x: string): string {
            return x
        }
    }
    
}
</script>

<style>

</style>
