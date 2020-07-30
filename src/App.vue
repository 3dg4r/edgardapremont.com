<script>
// import NavigationBar from '@/components/navigation-bar.vue';

export default {
  name: 'App',
  // components: {
  //   NavigationBar,
  // },
};
</script>

<template>
  <div id="app">
    <div v-cloak>
      <!-- NavigationBar></NavigationBar -->
      <router-view/>
    </div>
  </div>
</template>

<style>
[v-cloak] { display: none; }
</style>
