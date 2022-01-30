<template>
  <div class="home container">
    <div class="home-left">
      <h1>Hi, I'm Bobur</h1>
      <p>I was born in 2005. I am a frontend developer. I am from Fergana, Uzbekistan. This is my first personal website!</p>
      <div class="home-buttons">
        <button><a href="#">About me</a></button>
      </div>
      <div class="home-links">
        <a href="#"><i type='logo' class='bx bxl-telegram'></i></a>
        <a href="#"><i class='bx bxl-github' type='logo' ></i></a>
        <a href="#"><i class='bx bxl-instagram' type='logo' ></i></a>
      </div>
    </div>
    <div class="home-right"></div>
  </div>
</template>

<script>

</script>

<style scoped>
  
  .home {
    padding-top: 160px;
    color: tomato;
  }

  h1 {
    font-size: 70px;
  }

  p {
    font-size: 25px;
    margin-top: 8px;
  }

  .home-buttons {
    margin-top: 25px;
  }
  .home-buttons button {
    background: teal;
    padding: 15px 20px;
    border: none;
    border-radius: 4px;
  }
  .home-buttons button a {
    font-size: 20px;
    color: whitesmoke;

    padding: 15px 20px;
  }

  .home-links {
    margin-top: 15px;
  }
  .home-links a {
    font-size: 35px;
    color: #BC6D4F;

    margin-left: 15px;
  }

</style>