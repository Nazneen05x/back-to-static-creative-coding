<footer>
    <section class="star1"></section>
    <section class="star2"></section>
    <img
      class="footerimg"
      src="/visual-thinking-logo-footer.svg"
      alt="Visual thinking"
    />
  
    <ul class="ullinks">
      <li>Over</li>
      <li>Artikelen</li>
      <li>Tekenmethodes</li>
      <li>Kennisclips</li>
    </ul>
  
    <section>
      <h4>Contact</h4>
  
      <ul class="logoimglist">
        <li>
          <img class="logoimg" src="/instagram.svg" alt="instagram" />
        </li>
        <li>
          <img class="logoimg" src="/youtube.svg" alt="youtube" />
        </li>
        <li>
          <img class="logoimg" src="/linkedin.svg" alt="linkedin" />
        </li>
      </ul>
  
      <h5>© Charley Muhren, 2022</h5>
    </section>
  
    <section class="star"></section>
    <section class="star3"></section>
  </footer>
  
  <style>
    /* MOBILE STYLING*/
    footer {
      margin-top: 1.5em;
      padding: 1.5em;
      margin: -1em;
      background: linear-gradient(
        90deg,
        rgba(192, 190, 185, 1) 14%,
        rgba(9, 9, 64, 1) 54%
      );
    }
  
    .footerimg {
      width: 16em;
      margin-left: 2em;
      margin-bottom: 1em;
    }
  
    .logoimg {
      width: 1.5em;
    }
  
    ul {
      list-style: none;
      margin: 0em;
      font-family: var(--vtPrimaryFont);
      line-height: 1.5em;
      color: var(--white);
    }
  
    h4,
    h5 {
      font-family: var(--vtPrimaryFont);
      margin-left: 2.5em;
      color: var(--white);
    }
  
    /* SPARKLE ANIMATION */
    /* JellyPir.@tCoding (codepen) */
    .star {
      width: 6px;
      height: 6px;
      background-color: #feb51e;
      border-radius: 50%;
      opacity: 0;
      animation: sparkle 4s infinite alternate;
    }
  
    .star1 {
      margin-left: 20em;
      top: 2em;
      position: absolute;
      width: 6px;
      height: 6px;
      background-color: #feb51e;
      border-radius: 50%;
      opacity: 0;
      animation: sparkle 4s infinite;
    }
  
    .star2 {
      margin-left: 17em;
      top: 9em;
      position: absolute;
      width: 6px;
      height: 6px;
      background-color: #feb51e;
      border-radius: 50%;
      opacity: 0;
      animation: sparkle 4s infinite;
    }
  
    .star3 {
      margin-left: 19em;
      top: 15em;
      position: absolute;
      width: 8px;
      height: 8px;
      background-color: #feb51e;
      border-radius: 50%;
      opacity: 0;
      animation: sparkle 4s infinite;
    }
  
    @keyframes sparkle {
      50% {
        opacity: 0.4;
        transform: scale(0.5);
        box-shadow: 0px 0px 10px 5px #feb51e;
      }
      50% {
        opacity: 1;
        transform: scale(1);
        box-shadow: 0px 0px 10px 5px #feb51e;
      }
  
      100% {
        opacity: 0;
        transform: scale(1.5);
        box-shadow: 0px 0px 10px 5px #feb51e;
      }
    }
  
    /* DESKTOP STYLING */
    @media only screen and (min-width: 900px) {
      footer {
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 8em;
        height: 100%;
      }
  
      .logoimglist {
        display: flex;
        justify-content: space-evenly;
        margin-left: -2em;
      }
  
      ul {
        line-height: 1.5em;
      }
  
      .ullinks {
        margin-left: -5em;
      }
  
      /* SPARKLE ANIMATION */
      /* JellyPir.@tCoding (codepen) */
      .star {
        width: 8px;
        height: 8px;
        background-color: #feb51e;
        border-radius: 50%;
        opacity: 0;
        animation: sparkle 2s infinite alternate;
      }
  
      .star1 {
        margin-left: -18em;
        top: 4em;
      }
  
      .star2 {
        margin-left: 9em;
        top: 9em;
      }
  
      .star3 {
        margin-left: 80em;
        top: 9em;
      }
  
      @keyframes sparkle {
        50% {
          opacity: 0.4;
          transform: scale(0.5);
          box-shadow: 0px 0px 10px 5px #feb51e;
        }
        50% {
          opacity: 1;
          transform: scale(1);
          box-shadow: 0px 0px 10px 5px #feb51e;
        }
  
        100% {
          opacity: 0;
          transform: scale(1.5);
          box-shadow: 0px 0px 10px 5px #feb51e;
        }
      }
    }
  </style>
  