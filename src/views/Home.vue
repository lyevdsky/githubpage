<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
	https://github.com/lyevdsky/gitpag
    <HelloWorld msg="Welcome to Your Vue2.js App3"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>
