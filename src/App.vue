<template>
  <div id="app" class="fill flex-shrink-0">
    <nav class="navbar">
      <div class="container-fluid">
        <img src="logo.png" alt="" width="50px">
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Link</a>
            </li>
            <li class="nav-item">
              <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <router-view>
      
    </router-view>
  </div>
</template>
<script>
export default {};
</script>
<style>
@import url("https://fonts.googleapis.com/css2?family=Asap&display=swap");
body {
  padding: 0%;
  margin: 0;
  width: 100%;
  height: 100%;
  background: #202135;
  color: #fff;
  font-family: "Asap", sans-serif;
}
.nav-link {
  color: #fff;
}
</style>
