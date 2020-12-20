<template>
  <div>
    <Navbar />
    <div class="side-bar">
      <SideBar />
    </div>
    <div>
      <!-- <BackGround class="Background" /> -->
    </div>
    <nuxt class="screen"></nuxt>
  </div>
</template>

<script>
export default {
  data(){
    return {
      check: true,
    }
  }
};
</script>

<style scoped>
.Background {
  background: linear-gradient(0deg, #fae7eb, #ffffff) !important;
  color: red;
  top:-35%

}
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
@media only screen and (max-width: 1025px) {
  .side-bar {
    left: 40px;
    height: auto;
  }
}
@media only screen and (max-width: 768px) {
  .side-bar {
    display: none;
  }
}
.screen {
  padding-top: 10px !important;
  transition: 0.5s;
  background: linear-gradient(-90deg, #ffffff, #fae7eb);
}
</style>
