<script>
  let cards = [
    {
      src: "/src/img/badge 1.png",
      alt: "badge",
      title: "Supreme Beans",
      text: "Beans that provides great taste"
    },{
      src: "/src/img/coffee-beans 1.png",
      alt: "coffe beans",
      title: "High Quality",
      text: "We provide the highest quality"
    },{
      src: "/src/img/coffee-cup 1.png",
      alt: "coffee cup",
      title: "Extraordinary",
      text: "Coffee like you have never tasted"
    },{
      src: "/src/img/best-price 1.png",
      alt: "best price",
      title: "Affordable Price",
      text: "Our Coffee prices are easy to afford"
    },
  ]
</script>

<section class="section">
  <div class="titles">
    <h2>Why are we different?</h2>
    <p>We don’t just make your coffee, we make your day!</p>
  </div>
  <div class="cards">
    {#each cards as card}
      <div class="card">
        <img src={card.src} alt={card.alt}/>
        <h3>{card.title}</h3>
        <p>{card.text}</p>
      </div>
    {/each}
  </div>
  <div class="footer">
    <p>
      Great ideas start with great coffee, Lets help you achieve that
      <span class="resaltar">Get started today.</span>
    </p>
    <button class="button">Join Us</button>
  </div>
</section>

<style>
  .section {
    margin: 93px;
    display: flex;
    flex-direction: column;
    gap: 32px;
  }

  p {
    font-family: Playfair Display;
    font-size: 20px;
    font-weight: 400;
    line-height: 34px;
    letter-spacing: 0em;
    text-align: center;
    color: #707070;

  }

  .titles {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  

  .cards {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    gap: 20px;
  }


  .card {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 36px 40px;
    border: 1px solid #F9C06A6B;
    background: #FFF9F1;
    width: 380px;

    & img {
      height: 88px;
    } 
    & h3 {
      font-family: Playfair Display;
      font-size: 28px;
      font-weight: 700;
      line-height: 37px;
      letter-spacing: 0em;
      text-align: left;
    };
    & p {
      font-family: Playfair Display;
      font-size: 20px;
      font-weight: 400;
      line-height: 27px;
      letter-spacing: 0em;
      text-align: center;

    }
  } 

  .card:hover {
    background: linear-gradient(0deg, rgba(249, 192, 106, 0.42), rgba(249, 192, 106, 0.42)),
linear-gradient(0deg, #FFF9F1, #FFF9F1);



  }


  .footer {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    & .resaltar {
      font-family: Playfair Display;
      font-size: 30px;
      font-weight: 700;
      line-height: 40px;
      letter-spacing: 0em;
      text-align: center;
      display: block;
      color: #603809;
    }
    & 
    .button {
      padding: 14px 41px;
      border-radius: 24px;
      border: none;
      font-family: Playfair Display;
      font-size: 16px;
      font-weight: 700;
      line-height: 21px;
      letter-spacing: 0em;
      text-align: left;
      background: #F9C06A;
      box-shadow: 0px 6px 12px 0px #F9C06A38;


    }
  }

</style>