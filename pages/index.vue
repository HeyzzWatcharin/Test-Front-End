<template>
  <div>
    <div class="container">
      <div>
        <Card />
        <br />
        <SubContent class="mt-6" />
        <br />
        <div class="mb-2 columns" style="margin-left:45%">
          <div class="column">
            <ThirthContent />
          </div>
          <div class="column" style="margin-top:13%"><Fouth /></div>
        </div>
      </div>
    </div>
  </div>
</template>
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
