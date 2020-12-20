<template>
  <div>
    <RightSideBar  v-if="check" class="RightSide"  v-on:Show="ShowSide"   />
    <Navbar v-on:Show="ShowSide" />
    <SideBar/>
    <nuxt class="screen"></nuxt>
  </div>
</template>

<script>
export default {
  data() {
    return {
      check: false
    };
  },
  methods: {
    ShowSide() {
      // alert();
      if (this.check) {
        this.check = false;
      } else {
        this.check = true;
      }
    }
  }
};
</script>

<style scoped>
.RightSide {
  position: absolute;
  z-index: 100;
  align-items: center;
  margin-left: 80%;
}
.screen {
  padding-top: 10px !important;
  transition: 0.5s;
  background: linear-gradient(-90deg, #ffffff, #fae7eb);
}
</style>
