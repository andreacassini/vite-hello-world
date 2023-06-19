<script>
import HelloWorld from'./components/HelloWorld.vue';
import AppHero from './components/AppHero.vue';
import Logo from './components/Logo.vue';

export default {
  components:{
    HelloWorld,
    AppHero,
    Logo
  }
}
</script>

<template>
  <div>
    <Logo />
    <!-- <HelloWorld /> -->
    <AppHero />
  </div>
</template>
<style>
  
</style>