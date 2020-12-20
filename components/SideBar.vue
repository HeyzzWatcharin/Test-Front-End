<template>
  <div class="side-bar">
    <ul>
      <li>
        <div>
          <LogoSidebar class="Logo" />
        </div>
      </li>
      <li>
        <div class="Menu has-icons-left">
          <p>Home</p>
          <span class="is-left is-medium"><i class="fas fa-home"></i></span>
        </div>
      </li>
      <li>
        <div class="Menu has-icons-left">
          <p>Dashboard</p>
          <span class="is-left is-medium"
            ><i class="fas fa-chart-bar"></i
          ></span>
        </div>
      </li>
      <li>
        <div class="Menu has-icons-left">
          <p>รายรับ</p>
          <span class="is-left is-medium"
            ><i class="fas fa-chart-line"></i
          ></span>
        </div>
      </li>
      <li>
        <div class="Menu has-icons-left">
          <p>รายจ่าย</p>
          <span class="is-left is-medium"
            ><i class="fas fa-sort-amount-down"></i
          ></span>
        </div>
      </li>
      <li>
        <div class="Menu has-icons-left">
          <p>จัดการบิล</p>
          <span class="is-left is-medium"><i class="fas fa-receipt"></i></span>
        </div>
      </li>
      <li>
        <div class="Menu has-icons-left">
          <p>Mail Box</p>
          <span class="is-left is-medium"><i class="fas fa-envelope"></i></span>
        </div>
      </li>
    </ul>
  </div>
</template>
<style scoped>
.side-bar {
  z-index: 100;
  position: absolute;
  top: 120px;
  left: 80px;
  height: 90%;
  width: 250px;
  background: linear-gradient(0deg, #fae7eb, #ffffff);
  transition: 0.8s;
  overflow: hidden;
  border-radius: 30px;
}
.Menu {
  padding-bottom: 5%;
  padding-top: 5%;
}
.Logo {
  height: 100px;
  width: auto;
  margin-bottom: 30%;
  margin-top: 20%;
  margin-left: 30%;
}

li {
  position: relative;
}
.Menu:hover {
  background: rgba(252, 192, 205, 0.1);
  border-radius: 1000px 0px 0px 1000px;
  cursor: pointer;
}
li i {
  font-size: 25px;
  padding-left: 25%;
}
li p {
  font-size: 18px;
  font-family: p-light;
  position: absolute;
  left: 40%;
  /* top: 30px; */
  color: #504e63;
}

@media only screen and (max-width: 1025px) {
  .side-bar {
    left: 40px;
    height: auto;
  }
  li p {
    font-size: 16px;
  }
  li i {
    font-size: 22px;
    padding-left: 25%;
  }
  .Logo {
    height: 80px;
    align-items: center;
  }
}

@media only screen and (max-width: 769px) {
  .side-bar {
    display: none;
  }
  li p {
    font-size: 12px;
  }
  li i {
    font-size: 18px;
    padding-left: 15%;
  }
  .Logo {
    height: 70px;
    align-items: center;
  }
}
</style>
