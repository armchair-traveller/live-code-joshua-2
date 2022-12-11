<main>
  <figure>
    <h1>Wanted</h1>
    <p>Dead or Alive</p>
    <img src="/mugshot.png" alt="mugshot of Billy" />
    <figcaption>
      <h2>Billy the Kid</h2>
      <em>Armed & very dangerous</em>
      <h2>Reward</h2>
      <u>$50.000</u>
    </figcaption>
  </figure>
</main>

<style>
  @import url('https://fonts.googleapis.com/css?family=Ewert:400,500,600,700');
  @import url('https://fonts.googleapis.com/css?family=Ultra:400,500,600,700');
  main {
    min-height: 100vh;
    min-width: min-content;
    background-image: url('/wood_background.jpeg');
    display: grid;
    place-content: center;
    --brown: #291200;
    color: var(--brown);
    font-family: Ultra, serif;
    text-align: center;
  }
  h1 {
    font-family: Ewert, serif;
    font-size: 7rem;
    margin-bottom: -1rem;
  }
  p {
    font-size: 3rem;
  }
  h2 {
    font-size: 3rem;
  }
  figcaption h2 {
    font-size: 3.5rem;
  }
  em {
    font-size: 1.8rem;
  }
  em + h2 {
    font-size: 2.5rem;
  }
  figure {
    background-image: url('/poster.jpeg');
    background-size: 270px;
    margin: 4rem auto;
    width: 865px;
    padding: 0 10rem;
    padding-bottom: 2.5rem;
    box-shadow: 2px 4px 8px 3px #000000;
  }
  img {
    border: solid var(--brown) 3px;
    margin: 0 auto;
    width: 100%;
    filter: sepia(55%);
  }
  u {
    font-size: 4.8rem;
    text-decoration: underline double;
    text-underline-offset: 1rem;
    line-height: 1.1;
  }
</style>
