<template>
  <div>
    <h1 class="Text">My Work</h1>
    <div class="columns">
      <div class="column" v-for="(A, i) in Test" :key="i">
        <Card1 :Add="A.Detail" :Bill="A.Thai" />
      </div>
      <div class="column" v-if="MyData.length > 0">
        <div class="card ColorCard">
          <div class="card-content ">
            <div class="content has-text-centered CardPlus">
              <i class="fas fa-plus-circle fas fa-3x" @click="Fetch"></i>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      MyData: [
        { Detail: "In come", Thai: "เพิ่มรายรับ" },
        { Detail: "In come2", Thai: "เพิ่มรายรับ2" }
      ],
      Test: [{ Detail: "Add Bill", Thai: "เพิ่มบิล" }]
    };
  },
  methods: {
    Fetch() {
      this.MyData.reverse();
      if (this.MyData.length > 0) {
        const x = this.MyData.pop();
        this.Test.push(x);
        console.log(x);
      }
    }
  }
};
</script>
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
