<!-- <script>
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
      title: "SExtraordinary",
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
    <h1>Why are we different?</h1>
    <p>We don’t just make your coffee, we make your day!</p>
  </div>
  <div class="cards">
    {#each cards as card}
      <div class="card">
        <img src={card.src} alt={card.alt}/>
        <h2>{card.title}</h2>
        <p>{card.text}</p>
      </div>
    {/each}
  </div>
  <div class="footer">
    <p>
      Great ideas start with great coffee, Lets help you achieve that
      Get started today.
    </p>
    <button>Join Us</button>
  </div>
</section>

<style>
  .section {
    background-color: grey;
    margin: 93px;
    /* display: flex; */
    /* flex-direction: column; */
    /* align-items: space-between; space-around; space-evenly*/
    /* justify-content: space-around; */
  }

  .cards {
    background-color: blue;
    display: flex;
    flex-direction: row;    
  }

  .cards img {
    height: 88px;
  }

  .card h2 {
    font-family: Playfair Display;
    font-size: 28px;
    font-weight: 700;
    line-height: 37px;
    letter-spacing: 0em;
    text-align: left;

  }
</style> -->