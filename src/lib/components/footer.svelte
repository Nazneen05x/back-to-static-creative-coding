<footer>
  <img
    class="footerimg"
    src="/visual-thinking-logo-footer.svg"
    alt="footerlogo"
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
        <img class="logoimg" src="/instagram.svg" alt="instagramlogo" />
      </li>
      <li>
        <img class="logoimg" src="/youtube.svg" alt="youtubelogo" />
      </li>
      <li>
        <img class="logoimg" src="/linkedin.svg" alt="linkedinlogo" />
      </li>
    </ul>

    <h5>© Charley Muhren, 2022</h5>
  </section>
</footer>

<style>
  footer {
    margin-top: 1.5em;
    background-color: #f0f0f0;
    padding: 1.5em;
    margin: -1em;
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
  }

  h4,
  h5 {
    color: var(--vtDarkBlue);
    font-family: var(--vtPrimaryFont);
    margin-left: 2.5em;
  }

  @media only screen and (min-width: 900px) {
    footer {
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 8em;
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
  }
</style>
