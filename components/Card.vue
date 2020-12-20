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
            <div>
              <div><ImageCard class="ImageCard" /></div>
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

/* Mobile L */
@media only screen and (max-width: 1025px) {
  .title {
    font-size: 32px;
  }
  .subtitle {
    font-size: 18px;
  }
  .card {
    width: 480px;
    height: auto;
    margin-left: 40%;
  }
  .ImageCard {
    height: 150px;
    top: 20px;
  }
  .description {
    font-size: 24px;
  }
}
/* Mobile M */
@media only screen and (max-width: 769px) {
  .title {
    font-size: 22px;
  }
  .subtitle {
    font-size: 18px;
  }
  .card {
    margin-left: 55%;
    height: 120px;
    width: 280px;
 
  }
  .ImageCard {
    height: 120px;
    top: 80px;
    display: none;
  }
  .description {
    font-size: 16px;
  }
}
/* Mobile M */
@media only screen and (max-width: 426px) {
  .card {
    margin-left: 15%;
  }
}

@media only screen and (max-width: 376px) {
  .card {
    margin-left: 10%;
  }
}
@media only screen and (max-width: 321px) {
  .card {
    margin-left: 3%;
  }
}
</style>
