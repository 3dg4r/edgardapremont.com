<script>
// @ is an alias to /src
import Header from '@/components/header.vue';

export default {
  name: 'abut',
  components: {
    Header,
  },
};
</script>

<template>
  <div class="about">
    <Header />
    <div>
      <h2>About Me</h2>
    </div>
  </div>
</template>
