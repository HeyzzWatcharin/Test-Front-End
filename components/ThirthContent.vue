<template>
  <div class="Th">
    <div>
      <p>
        <b class="mr-5 is-size-4">Total</b>15 January, 2021
      </p>
      <br />
      <div class="size">
        <div class="columns">
          <div class="column is-5">
            <p style="font-size:16px">รายได้(Income)</p>
            <p><b style="font-size:21px">฿ 123,456.-</b></p>
          </div>
          <div class="column is-1">
            <div class="vertical-line" style="height: 45px;"></div>
          </div>
          <div class="column">
            <p style="font-size:16px">รายจ่าย(Expend)</p>
            <p><b style="font-size:21px">฿ 12,345.-</b></p>
          </div>
        </div>
        <div></div>
      </div>
    </div>
    <div class="card">
      <div class="card-content">
        <div class="content has-text-centered">
          <p class="is-size-5 subtitle">ยอดคงเหลือสุทธิ( Net balance )</p>
          <p class="is-size-3 title" style="color:#7947B5">
            <b>฿ 123,456.-</b>
          </p>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
p {
  font-family: dx-text;
}
p b {
  font-family: p-bold;
}
.card {
  border-radius: 0 30px 30px 30px;
}
.Th {
  /* margin-left: 45%; */
  width: 350px;
}
.size {
  width: 100%;
}
div.vertical-line {
  width: 1px; /* Line width */
  background-color: black; /* Line color */
  height: 100%; 
  float: left; 
}
</style>
