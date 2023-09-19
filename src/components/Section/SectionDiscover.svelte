<script>
  // let src = "../../img/tacita_coffee.png"
  let src = "/src/img/tacita_coffee.png"
</script>

<section class="section">
  <div class="description">
    <h1>Discover the best coffee</h1>
    <p>
      Bean Scene is a coffee shop that provides you with quality coffee that helps boost your productivity and helps build your mood. Having a cup of coffee is good, but having a cup of real coffee is greater. There is no doubt that you will enjoy this coffee more than others you have ever tasted.     
    </p>
    <button class="button">
      Learn More
    </button>
  </div>
  <img {src} alt="coffe" />
</section>

<style>
  .section {
    display: flex;
    flex-direction: row;
    margin: 93px;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;

  }

  h1 {
    font-weight: 700;
    font-size: 54px;
    line-height: 72px;
  }

  p {
    font-weight: 400;
    font-size: 20px;
    line-height: 34px;
    letter-spacing: 0em;
    text-align: left;
    width: 585px;
    font-family: 'Playfair Display', bold;

  }

  img {
    width: 500px;
    height: 484px;
  }

  .description {
    /* background-color: blue; */
    display: flex;
    flex-direction: column;
    row-gap: 29px;    
  }

  .button {
    border-radius: 24px;
    border: none;
    height: 48px;
    width: 134px;
    background-color: #F9C06A;
    color: #1E1E1E;
    font-size: 16px;
    font-weight: 700;
  }
</style>