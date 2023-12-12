<nav>
  <img class="popartrondjes" src="/rondjes.svg" alt="rondjes" />

  <ul>
    <li><a href="/#">Tekenmethodes</a></li>
    <li><a href="#kennisclips">Kennisclips</a></li>
  </ul>

  <img src="/vtHBO-Logo.svg" alt="vtHBO-Logo" />

  <ul>
    <li><a href="#overons">Over</a></li>
    <li><a href="/#">Artikelen</a></li>
  </ul>
  <p aria-label="AAA">AAAH!!</p>
  <img class="popartwolk" src="/popartwolk.svg" alt="popartwolk" />
</nav>

<style>
  /* DESKTOP STYLING */
  nav {
    background-color: #ffe1a5;
    display: flex;
    justify-content: center;
    align-items: center;
    margin: -1em;
    padding: -1em;
    gap: 2em;
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

  p {
    font-family: var(--vtPrimaryFont);

    font-size: 31px;
    font-weight: bold;
    position: absolute;
    left: 39em;
    z-index: 1;
    rotate: 10deg;
    top: 2em;
    color: white;
    text-shadow: 2px 2px 4px #000000;
    font-style: oblique;
  }

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
  }

  a:hover {
    color: var(--vtRed-50);
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

  .popartrondjes {
    height: auto;
    width: 12em;
    position: relative;
    left: -12em;
    top: 0em;
  }

  /* MOBILE STYLING*/
  @media only screen and (max-width: 767px) {
    ul {
      display: none;
    }
  }
</style>
