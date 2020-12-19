<template>
  <div class="card">
    <div class="card-content">
      <div class="content">
        <div class="columns">
          <div class="column is-half description">
            <p class="title is-3 ">Hi,<em> Linna Li</em></p>
            <p class="subtitle is-5">Have a nice day at work.</p>
          </div>
          <div class="column">
            <div><ImageCard class="ImageCard" /></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.description {
  color: #000;
  margin-top: 2%;
  margin-left: 5%;
}

.description em {
  color: #7947B5;
}
.ImageCard {
  height: 180px;
  width: auto;
  position: fixed;
  z-index: 2;
  margin-left: 2%;
  top: 12%;
}
.card {
  width: 700px;
  height: 150px;
  border-radius: 30px;
  margin-left: 45%;
  margin-top: 5%;
}
</style>
