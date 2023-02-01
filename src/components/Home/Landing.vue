<script setup>

</script>

<template>
  <div class="landing">
    <video class="background-video" autoplay loop muted>
      <source src="@/assets/background.mp4" type="video/mp4">
    </video>
    <h1 class="title">PARADOXA</h1>
  </div>
</template>

<style lang="scss" scoped>
@use '@/assets/styles/_colors.scss';
@use '@/assets/styles/_fonts.scss';

.background-video {
  height: 100vh;
  width: 100vw;
  object-fit: cover;
  position: absolute;
  left: 0;
  right: 0;
  top: 0;
  bottom: 0;
  z-index: -1;
}

</style>
