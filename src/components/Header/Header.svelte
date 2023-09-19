<script>
  import coffe_image from "../../img/coffee_image.jpg"
</script>

<div class="bg_header">
  <img src={coffe_image} alt="Coffe_image">
  <div class="content">
    <header>
      <div class="bg_header_nav container">
        <p class="bg_header_title">Bean Scene</p>
        <nav class="bg_header_a">
          <a href="">Home</a>
          <a href="">Menu</a>
          <a href="">About Us</a>
          <a href="">Contact Us</a>
        </nav>
        <div class="bg_header_login">
          <a href="">Sing In</a>
          <button class="button">SignUp</button>
        </div>
      </div>
    </header>
    <div class="info_title container">  
      <div class="info_title_container">
        <p>We've got your morning covered with</p>
        <p class="info_title_container_title">Coffee</p>
        <p class="info_title_container_subtitle">It is best to start your day with a cup of coffe. Discover the best flavours coffee you will ever have. We provide the best for our custumers.</p>
        <button class="button">Order Now</button>
      </div>
      
    </div>
  </div>
</div>


<style>
  .bg_header a{
    color: #fff;
  }
  .bg_header{
    position: relative;
    height: 100vh;
  }
  .bg_header .content{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
  }
  .bg_header img{
    width: 100%;
    height: 100%;
  }

  .bg_header_nav{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    padding: 1.3rem 0;
    align-items: center;
  }

  .bg_header_title{
    color: var(--color-white);
    font-size: 35px
  }

  .bg_header_title:hover{
    cursor: pointer;
  }

  .bg_header_a{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    gap: 1.5rem;
  }

  .bg_header_login{
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 1.5rem;
  }

  .info_title p{
    color: var(--color-white);
  }

  .info_title_container{
    margin-top: 5%;
    width: 50%;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    gap: 1rem;
  }

  .info_title_container p{
    font-family: 'Playfair Display', serif;
    font-size: 22px;
  }

  .info_title_container p.info_title_container_title{
    font-size: 150px;
    font-family: 'Clicker Script', cursive;
  }

  .info_title_container_subtitle{
    line-height: 2.3rem;
  }
  
  /* DESKTOP */

  @media (min-width: 1224px){
    .container{
      max-width: 1200px;
      margin: 0 auto;
    }

  }

  /* TABLETA */

  @media (max-width: 1223px){
    .container{
      max-width: 900px;
      margin: 0 auto;
    }
  }

  @media (max-width: 950px){
    .container{
      max-width: 700px;
      margin: 0 auto;
    }
    .info_title_container p.info_title_container_title{
      font-size: 100px;
    }

    .info_title_container p{
      font-size: 17px;
    }
  }

  @media (max-width: 750px){
    .bg_header_nav.container{
      display: flex;
      flex-direction: column;
    }
    .bg_header_login{
      display: none;
    }
    .info_title.container{
      display: flex;
      justify-content: center;
      align-items: center;
    }
    .info_title_container {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }
  }



</style>