<template>
  <div class="home">
    <HelloWorld />
    <header><p>this is a header paragraph</p></header>
    <h1>frankolious fiddles </h1>
  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
