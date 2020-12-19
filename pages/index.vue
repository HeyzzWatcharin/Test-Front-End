<template>
  <div>
    <div class="container">
      <div>
        <Card />
        <br />
        <SubContent class="mt-6" />
      </div>
      <div></div>
    </div>
  </div>
</template>

<script>
export default {};
</script>
<style>
.BackGround {
  z-index: 1;
}
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  /*
  justify-content: center;
  align-items: center;
  text-align: center; */
  z-index: 2;
}
</style>
