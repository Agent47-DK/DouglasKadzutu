<template>
  <MainNav/>
  <HomeSection/>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import HelloWorld from './components/HelloWorld.vue';
import MainNav from './components/MainNav.vue';
import HomeSection from './views/HomeSection.vue'

@Options({
  components: {
    MainNav,
    HelloWorld,
    HomeSection,
    
  },
})
export default class App extends Vue {}
</script>

<style>

</style>
