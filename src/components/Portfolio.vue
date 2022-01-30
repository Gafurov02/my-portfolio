<template>
  <div class="portfolio container">
    <div class="portfolio-top">
      <h1>My projects</h1>
      <span>Check this</span>
    </div>
    <div class="portfolio-bottom">
      <div class="portfolio-first-project">
        <img src="../assets/portfolio-1.jpg" alt="">
        <div class="portfolio-project-text">
          <h3>Landing page Theatre</h3>
          <button><a href="https://gafurov02.github.io/-/" target="blank">Demo<i class='bx bx-link-alt'></i></a></button>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
  
  .portfolio {
    padding-top: 160px;
    color: tomato;
  }

  .portfolio-top {
    text-align: center;
  }
  .portfolio-top h1 {
    font-size: 45px;
    letter-spacing: 2px;
  }
  .portfolio-top span {
    display: block;
    font-size: 30px;
    letter-spacing: .5px;
    margin-top: 15px;
  }

  .portfolio-bottom {
    margin-top: 50px;
  }
  .portfolio-first-project {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
  }
  .portfolio-first-project img {
    width: 650px;
    height: 365px;
    
  }
  .portfolio-project-text {
    margin-left: 50px;
  }
  .portfolio-project-text h3 {
    font-size: 32px;
  }
  .portfolio-project-text button {
    margin-top: 50px;

    background: teal;
    padding: 15px 20px;
    border: none;
    border-radius: 4px;
  }
  .portfolio-project-text button a {
    font-size: 20px;
    color: whitesmoke;

    padding: 15px 20px;
  }
  .portfolio-project-text button i {
    margin-left: 5px;
  }

</style>