<script>
  let backgroundImage = "url(abstract-comic.avif)";
</script>

<nav style="background-image: {backgroundImage};">
  <ul>
    <li><a href="/#">Tekenmethodes</a></li>
    <li><a href="/kennisclips">Kennisclips</a></li>
  </ul>
  
  <a href="/">
    <img src="/vtHBO-Logo.svg" alt="vtHBO-Logo" />
  </a>

  <ul>
    <li><a href="/overons">Over</a></li>
    <li><a href="/#">Artikelen</a></li>
  </ul>

  <p aria-label="AAA">AAAH!!</p>

  <img class="popartwolk" src="/popartwolk.svg" alt="popartwolk" />
</nav>

<style>
  /* DESKTOP STYLING */
  nav {
    background-blend-mode: soft-light;
    background-size: cover;
    background-repeat: no-repeat;
    background-color: #ffe1a5;
    display: flex;
    justify-content: center;
    align-items: center;
    margin: -1em;
    gap: 2em;
    view-transition-name: nav;
  }

  ul {
    list-style: none;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  a {
    text-decoration: none;
    font-family: var(--vtPrimaryFont);
    color: var(--vtDarkBlue);
    font-weight: bold;
    margin: 1em;
  }

  a:hover {
    color: var(--vtRed-50);
  }

  p {
    font-family: var(--vtPrimaryFont);
    font-size: 31px;
    font-style: oblique;
    font-weight: bold;
    color: white;
    text-shadow: 2px 2px 4px #000000;
    position: absolute;
    width: 8vw;
    margin-left: 28em;
    z-index: 1;
    rotate: 10deg;
  }

  /* P ANIMATION */
  @keyframes AAA-animation {
    0% {
      scale: 1;
    }
    100% {
      scale: 2;
    }
  }

  p[aria-label="AAA"] {
    animation-name: AAA-animation;
    animation-duration: 1s;
    animation-iteration-count: infinite;
    animation-direction: alternate;
  }

  img {
    height: auto;
    width: 4em;
  }

  .popartwolk {
    height: auto;
    width: 15em;
    position: relative;
    left: 5em;
  }

  /* MOBILE STYLING*/
  @media only screen and (max-width: 48em) {
    nav {
      margin: -1em;
      padding: 3em;
    }

    ul {
      display: none;
    }

    p {
      display: none;
    }

    .popartwolk {
      display: none;
    }
  }
</style>
