<template>
  <div class="home">
    <Landing />
  </div>
</template>

<script>
// @ is an alias to /src
import Landing from '@/components/Home/Landing.vue';

export default {
  name: 'Home',
  components: {
    Landing,
  },
};
</script>
