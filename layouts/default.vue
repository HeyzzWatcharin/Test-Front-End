<template>
  <div>
    <Navbar />
    <div class="side-bar">
      <SideBar />
    </div>
    <nuxt class="screen"></nuxt>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.side-bar {
  z-index: 1000;
  position: fixed;
  top: 120px;
  left: 50px;
  height: 100%;
  width: 250px;
  background:linear-gradient(0deg,#FAE7EB,#FFFFFF);
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
