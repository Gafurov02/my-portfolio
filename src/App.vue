<template>
  <div class="app">
    <div class="nav nav-container">
      <div id="nav">
        <div class="nav-left">
          <router-link to="/">#BoburGafurov</router-link>
        </div>
        <div class="nav-right">
          <router-link to="/portfolio">Portfolio</router-link>
          <router-link to="/about">About</router-link>
        </div>
      </div>
    </div>
    <router-view/>
  </div>
</template>

<script>

</script>


<style>
  * {
    margin: 0;
    text-decoration: none;
    font-family: 'Supermercado One', cursive;
  }

  .app {
    width: 100%;
    height: 100%;
    background: #500805;
    position: fixed;
  }

  .nav {
    box-shadow: 0 5px 15px #0c0c0cde;
    background: transparent;
    backdrop-filter: blur(5px);
  }
  .nav-container {
    padding: 0 80px;
  }

  #nav {
    display: flex;
    justify-content: space-between;
    padding: 8px 0;
  }
  #nav a.router-link-exact-active {
    color: #9D331F;
  }
  #nav a {
    color: #BC6D4F;
    transition: .2s linear;
  }
  #nav a:hover {
    color: #9D331F;
  }
  #nav .nav-left a {
    font-size: 25px;
  }

  .nav-right a {
    margin-left: 15px;
  }

  .container {
    padding: 0 160px;
  }

</style>
