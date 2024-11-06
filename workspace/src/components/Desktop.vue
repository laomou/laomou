<template>
  <div class="desktop">
  </div>
</template>

<script>
export default {
  name: "Desktop",
  methods: {
    openWindow(windowName) {
      alert(`Opening ${windowName}`);
    }
  }
}
</script>

<style scoped>
.desktop {
  position: relative;
  width: 100%;
  height: 100vh;
  background: url('/src/assets/wallpaper.jpg') no-repeat center center;
  background-size: cover;
  overflow: hidden;
}
</style>
