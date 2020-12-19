<template>
  <div class="card">
    <div class="card-content">
      <div class="content">
        <div class="columns">
          <div class="column is-half">
            <div class=" description">
              <p class="title is-3 ">Hi,<em> Linna Li</em></p>
              <p class="subtitle is-5">Have a nice day at work.</p>
            </div>
          </div>
          <div class="column">
            <div class="is-justify-content-flex-end">
              <div><ImageCard class="ImageCard is-right" /></div>
            </div>
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
  color: #7947b5;
}
.ImageCard {
  height: 180px;
  width: auto;
  float: right;
  position: relative;
  z-index: 100;
  top: -30px;
}
.card {
  width: 700px;
  height: 150px;
  border-radius: 30px;
  margin-left: 45%;
  margin-top: 5%;
}
</style>
