<style>
  figure {
    float: right;
    margin: -3em -7em 2em 2em;
    max-width: 400px;
  }

  figure img {
    border-radius: 8px;
  }

  @media (max-width: 520px) {
    p {
      font-size: 1rem;
    }
  }
  @media (max-width: 1020px) {
    figure {
      margin: 0 1em 2em;
      width: 40%;
    }
  }
</style>

<svelte:head>
  <title>About - Lance Vadla</title>
</svelte:head>

<div class="container">
  <h1>About</h1>
  <figure>
    <img src='marcel-strauss-moReXaMWSzQ-unsplash.jpg' alt='A minimal keyboard.'>
    <figcaption>Photo by <a href="https://unsplash.com/@martzzl" target="_blank">Marcel Strauß</a> on Unsplash</figcaption>
  </figure>
  <p>Hi, I'm Lance. I'm a software engineer from Dallas, Texas. 🤠 I currently work with HTML, CSS, JavaScript, and React. I also like using Svelte.
  </p>
  <p>You can see some of my work on
    <a rel="noopener" href="https://www.github.com/lvadla" target="_blank" aria-label="link to Lance's GitHub profile">GitHub</a>,
    or read about my professional experience on 
    <a rel="noopener" href="https://www.linkedin.com/lance-vadla" target="_blank" aria-label="link to Lance's LinkedIn profile">LinkedIn</a>.
    If you prefer email, say  
    <a href="mailto:hello@lancevadla.com" aria-label="contact Lance via email">hello@lancevadla.com</a>.
  </p>
  <p>I have a background in engineering, but professionally, I am interested in why we write bad software.</p>
</div>
