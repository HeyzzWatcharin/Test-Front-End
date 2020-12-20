<template>
  <div class="card cardS">
    <div class="card-content">
      <div class="content">
        <div class="rows">
          <div class="row is-full">
            <div class="columns">
              <div class="column is-6">
                <p class="is-size-6"><b>Schedule Calendar</b></p>
              </div>
              <div class="column is-2">
                <span><i class="fas fa-chevron-left"></i></span>
                <span><i class="fas fa-chevron-right"></i></span>
              </div>

              <div class="column is-3">
                <div class="button is-small">
                  <span class="icon is-small">
                    <i class="fas fa-calendar-alt"></i>
                  </span>
                  <span>Jan, 2021</span>
                </div>
              </div>
            </div>
          </div>
          <div class="row is-full">
            <div class="columns has-text-centered mt-2">
              <div class="column">
                <p class="mt-2">Sun</p>
                <p>12</p>
              </div>
              <div class="column">
                <p class="mt-2">Mon</p>
                <p>13</p>
              </div>
              <div class="column">
                <p class="mt-2">Tue</p>
                <p>14</p>
              </div>
              <div
                class="column"
                style="  background-color: #9e43b8;
  color: white;border-radius: 20px;"
              >
                <p class="mt-2">Wed</p>
                <p>15</p>
              </div>
              <div class="column">
                <p class="mt-2">Thu</p>
                <p>16</p>
              </div>
              <div class="column">
                <p class="mt-2">Fri</p>
                <p>17</p>
              </div>
              <div class="column ">
                      <p class="mt-2">Sun</p>
                      <p>12</p>
                  </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.is-2:hover{
  cursor: pointer;
}
.rows {
  display: flex;
  flex-direction: column;
}
.button {
  background-color: #fae7eb;
  color: #7947b5;
}
.cardS {
  border-radius: 30px;
  /* margin-left: 45%; */
  width: 450px;
}
</style>
