<template>
  <div>
    <div class="sidebar">
      <div class="columns">
        <div class="column is-half" style="color:#ECA1A6">
          <i @click="$emit('Show')" class="fas fa-times is-size-4" ></i>
        </div>
        <div class="column has-text-right">
          <i class="fas fa-ellipsis-v"></i>
        </div>
      </div>
      <ul>
        <li>
          <div class=" has-text-centered">
            <Profile class="Logo" />
          </div>
        </li>
        <li class=" has-text-centered">
          <div class="Menu has-icons-left">
            <p style="font-size:22px">
              Linna Li<span class="is-size-6 ml-2"><i class="fas fa-pen"></i></span>
            </p>
          </div>
        </li>
        <li class=" has-text-centered">
          <div class="Menu has-icons-left mb-5">
            <p style="font-size:12px">
              Marketing<span class="dot ml-2"></span>
            </p>
          </div>
        </li>
        <li class=" has-text-centered">
          <div>
            <p style="font-size:16px;text-decoration: underline;">
              Edit Profile Picture
            </p>
          </div>
        </li>
        <li>
          <div class="columns" style="font-size:12px">
            <div class="column is-half has-text-right"><p>Code</p></div>
            <div class="column is-left"><p>: 123456789</p></div>
          </div>
        </li>
        <li>
          <div class="columns" style="font-size:12px">
            <div class="column is-half has-text-right"><p>FirstName</p></div>
            <div class="column"><p>: Linna</p></div>
          </div>
        </li>
        <li>
          <div class="columns" style="font-size:12px">
            <div class="column is-half  has-text-right"><p>LastName</p></div>
            <div class="column"><p>: Linnai</p></div>
          </div>
        </li>
        <li>
          <div class="columns" style="font-size:12px">
            <div class="column is-half  has-text-right"><p>NickName</p></div>
            <div class="column"><p>: Linnai</p></div>
          </div>
        </li>
        <li>
          <div class="columns" style="font-size:12px">
            <div class="column is-half has-text-right"><p>Position</p></div>
            <div class="column"><p>: Sales and Marketing</p></div>
          </div>
        </li>
        <li>
          <div class="columns" style="font-size:12px">
            <div class="column is-half  has-text-right"><p>Team</p></div>
            <div class="column"><p>: Sailor Moon</p></div>
          </div>
        </li>
        <li>
          <div class="columns" style="font-size:12px">
            <div class="column is-half  has-text-right"><p>Contact</p></div>
            <div class="column"><p>: Contact</p></div>
          </div>
        </li>
        <li>
          <div class="columns" style="font-size:12px">
            <div class="column is-half  has-text-right"><p>Bank</p></div>
            <div class="column"><p>: K-Bank</p></div>
          </div>
        </li>
        <li>
          <div class="columns" style="font-size:12px">
            <div class="column is-half  has-text-right"><p>Acc co.</p></div>
            <div class="column"><p>: 12-3456-789</p></div>
          </div>
        </li>
        <li>
          <div class="columns" style="font-size:12px">
            <div class="column is-half  has-text-right"><p>Amount</p></div>
            <div class="column"><p>: 12,000-</p></div>
          </div>
        </li>
      </ul>
    </div>
  </div>
</template>
<style scoped>
.dot {
  height: 8px;
  width: 8px;
  background-color: rgb(81, 245, 6);
  border-radius: 50%;
  display: inline-block;
}
i:hover {
  cursor: pointer;
}
.columns {
  margin-top: 5%;
  margin-left: 2%;
  margin-right: 2%;
}
.Logo {
  height: 100px;
  width: auto;
  border-color: #ffaf90;
  /* margin-left: 30%; */
}
.sidebar {
  margin: 0;
  padding: 0;
  width: 300px;
  background-color: #ffffff;
  position: fixed;
  height: 100%;
  overflow: auto;
}

@media screen and (max-width: 700px) {
  .sidebar {
    width: 100%;
    height: auto;
    position: relative;
  }
}
</style>
