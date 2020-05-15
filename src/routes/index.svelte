<style>
  .home-container {
    align-items: center;
    display: flex;
    flex: 1;
    flex-flow: row-reverse;
    justify-content: center;
    margin: 2em 0;
    min-height: 400px;
  }

  .home-copy {
    flex: 1;
    text-align: right;
  }

  h1 {
    font-weight: 700;
    margin-bottom: 0.5em;
  }

  figure {
    margin: 0 1em;
    text-align: center;
  }

  figcaption {
    font-size: .8em;
    font-style: italic;
  }

  img {
    width: 100%;
    max-width: 400px;
  }

  @media (max-width: 1020px) {
    img {
      max-width: 300px;
    }
  }

  @media (max-width: 800px) {
    .home-container {
      flex-direction: column;
    }

    .home-copy {
      flex: 0;
      padding-bottom: 2em;
      text-align: center;
    }
  }
</style>

<svelte:head>
  <title>Welcome! - Lance Vadla's Blog</title>
</svelte:head>

<div class="home-container">
  <div class="home-copy">
    <h1>Welcome to my blog!</h1>
  </div>

  <figure>
    <img alt='Person browsing the mobile web' src='undraw-illustration.svg'>
    <figcaption>Illustration thanks to <a href="https://undraw.co" target="_blank">Undraw</a></figcaption>
  </figure>
</div>
