<template>
  <div>
    <Navbar />
    <div class="side-bar">
      <SideBar />
    </div>
    <div class="Background">
      <!-- <BackGround /> -->
    </div>
    <nuxt class="screen"></nuxt>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.side-bar {
  z-index: 100;
  position: absolute;
  top: 120px;
  left: 80px;
  height: 90%;
  width: 250px;
  background: linear-gradient(0deg, #fae7eb, #ffffff);
  transition: all 0.5s ease;
  overflow: hidden;
  border-radius: 30px;
}
.screen {
  padding-top: 10px !important;
  transition: 0.5s;
  background: linear-gradient(-90deg, #ffffff, #fae7eb);
}
</style>
