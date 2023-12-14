<script>
  import Header from "../../lib/components/header.svelte";
  let backgroundImage = "url(giphy.gif)";
</script>

<Header />

<section style="background-image: {backgroundImage};">
  <section class="smoke-wrap">
    <img class="smoke" src="/smoke.webp" alt="smoke" />
  </section>

  <h1>Over het platform</h1>

  <p>
    “Hoe kan ik studenten meer laten tekenen en ze laten inzien dat een tekening
    een heel geschikt communicatiemiddel is?” vroeg Charley Muhren, docent aan
    de HvA en ontwerper van de tekenmethode Tekenen, spelen, delen, zich af
    voordat ze aan dit platform begon.
  </p>

  <p>
    Ze ontving een Comeniusbeurs voor haar plan om een platform te ontwikkelen
    waarmee studenten al aan het begin van hun studie zouden leren om tekenen te
    gebruiken als communicatiemiddel en heeft de afgelopen anderhalf jaar
    onderzocht welke tekenmethodes geschikt zouden zijn voor studenten en
    docenten om te gebruiken tijdens hun studie. Door de werkvormen te
    categoriseren aan de hand van leerdoelen die weer gekoppeld zijn aan de
    taxonomie van ‘Betekenisvol leren’ (Dee Fink, 2003), kunnen zowel studenten
    als docenten gemakkelijk zoeken in welke situatie en met welk doel een
    tekenmethode te gebruiken is.
  </p>

  <p>
    In de kennisclips wordt uitgelegd waarom tekenen voor bepaalde doelen goed
    te gebruiken is en wat de resultaten van de methodes kunnen zijn.
  </p>

  <p>
    In de mini-cursussen worden de basisprincipes van ‘visual thinking’
    uitgelegd en wordt verwezen naar andere visual thinkers en bronnen.
  </p>
</section>

<style>
  section {
    padding: 3em;
    margin: -1em;
    background-color: black;
    /* background-image: url(giphy.gif); */
    background-repeat: no-repeat;
    background-position-x: 58em;
    background-blend-mode: hard-light;
  }

  img {
    width: 17vw;
    margin-left: -27em;
  }

  h1 {
    font-family: var(--vtPrimaryFont);
    color: orange;
  }

  p {
    line-height: 1.5em;
    font-size: 17px;
    font-family: var(--vtSecondaryFont);
    color: whitesmoke;
    width: 41vw;
  }

  .smoke-wrap {
    transform: translateX(-50%);
    position: absolute;
    left: 50%;
  }

  .smoke {
    transform-origin: 50% 50%;
    transform: translateX(-50%);
  }

  .smoke {
    animation: smoke 3s linear infinite;
  }

  @keyframes smoke {
    0% {
      filter: blur(0px);
      transform: translateY(0px) scale(-1, 1);
      opacity: 0;
    }

    25% {
      filter: blur(3px);
      transform: translateY(-10px) scale(-1, 1.05);
      opacity: 0.5;
    }

    50% {
      filter: blur(5px);
      transform: translateY(-20px) scale(-1, 1.1);
      opacity: 1;
    }

    75% {
      filter: blur(5px);
      transform: translateY(-30px) scale(-1, 1.1);
      opacity: 0.5;
    }

    100% {
      filter: blur(7px);
      transform: translateY(-40px) scale(-1, 1.2);
      opacity: 1;
    }
  }

  iframe {
    margin-left: 1em;
  }
</style>
