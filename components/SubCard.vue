<template>
  <div>
    <h1 class="Text">My Work</h1>
    <div class="columns">
      <div class="column">
        <div class="card">
          <div class="card-image">
            <figure class="image has-text-centered mt-4">
              <FigureCard class="Figure" />
            </figure>
          </div>
          <div class="card-content">
            <div class="content has-text-centered">
              <p class="title is-4">Add Bill</p>
              <p class="subtitle is-6">เพิ่มบิล</p>
            </div>
          </div>
        </div>
      </div>
      <div class="column">
        <div class="card ColorCard">
          <div class="card-content ">
            <div class="content has-text-centered CardPlus">
              <i class="fas fa-plus-circle fas fa-3x"></i>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.Text {
  margin-left: 45%;
  font-size: 22px;
  font-weight: bold;
}
i:hover {
  cursor: pointer;
}
.ColorCard {
  background-color: transparent;
}
.CardPlus {
  margin-top: 60%;
  color: #eca1a6;
}
.columns {
  margin-left: 30%;
}
.card {
  width: 200px;
  height: 280px;
  border-radius: 30px;
  margin-left: 45%;
  margin-top: 5%;
}
@media only screen and (max-width: 1025px) {
  .Figure {
    height: 130px;
    width: 130px;
  }
  .card {
    height: 250px;
  }
  .CardPlus {
    margin-top: 50%;
  }
}
@media only screen and (max-width: 769px) {
  h1 {
    margin-left: 35%;
  }
  .Figure {
    height: 120px;
    width: 120px;
  }
  .card {
    height: 250px;
  }
  .CardPlus {
    margin-top: 50%;
  }
}

@media only screen and (max-width: 426px) {
  .Text {
    margin-left: 33%;
  }
  .card {
    height: 250px;
    margin-left: 0%;
  }
  .CardPlus {
    margin-top: 50%;
  }
  .columns {
    margin-left: 20%;
  }
}


@media only screen and (max-width: 376px) {
  .Text {
    margin-left: 28%;
  }
  .columns {
    margin-left: 15%;
  }
}

@media only screen and (max-width: 321px) {
  .Text {
    margin-left: 20%;
  }
  .columns {
    margin-left: 8%;
  }
}
</style>
