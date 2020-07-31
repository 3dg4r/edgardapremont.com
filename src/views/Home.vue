<script>
// @ is an alias to /src
import Header from '@/components/header.vue';

export default {
  name: 'home',
  components: {
    Header,
  },
};
</script>

<template>
  <div class="home">
    <Header />
    <div class="main"></div>
  </div>
</template>
