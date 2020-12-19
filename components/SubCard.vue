<template>
  <div class="columns">
    <div class="column">
      <div class="card">
        <div class="card-image">
          <figure class="image has-text-centered mt-4">
            <FigureCard />
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
</template>

<style scoped>
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
</style>
