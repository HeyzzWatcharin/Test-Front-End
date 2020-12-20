<template>
  <div class="BackGround">
    <nav class="navbar" role="navigation" aria-label="main navigation">
      <div class="navbar-brand">
        <a class="navbar-item" href="#">
          <Logo class="logo" />
        </a>
        <a
          role="button"
          class="navbar-burger"
          aria-label="menu"
          aria-expanded="false"
          data-target="navbarBasicExample"
        >
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
        </a>
      </div>

      <div class="navbar-menu">
        <div class="navbar-end">
          <div class="navbar-item">
            <i class="fas fa-lg fa-cog mr-5" style="color:#7947B5;"></i>
            <i class="fas fa-lg fa-bell mr-5" style="color:#7947B5;"></i>
            <div class="navbar-item has-dropdown">
              <a class="navbar-link">
                <Profile class="ImageProfile mr-4" />
                <span>
                  <p class="mr-2 is-size-5"><b>Linna Li</b></p>
                  <p class="is-size-6">Marketing <span class="dot"></span></p>
                </span>
              </a>

              <div class="navbar-dropdown">
                <a class="navbar-item">
                  Overview
                </a>
                <a class="navbar-item">
                  Elements
                </a>
                <a class="navbar-item">
                  Components
                </a>
                <hr class="navbar-divider" />
                <div class="navbar-item">
                  Version 0.6.2
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </nav>
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
h1 {
  font-size: 16px;
}
p {
  font-size: 12px;
}
.navbar {
  background: linear-gradient(#fcf3f4, #fcdceb);
}
.logo {
  margin-left: 20%;
}
.navbar-menu {
  margin-right: 2%;
}
.ImageProfile {
  width: auto;
  height: 45px;
}
</style>
