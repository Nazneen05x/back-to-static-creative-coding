<section id="kennisclips" class="kennisclips">
  <h1>hoiu</h1>
  <p>hydunjshbfyusjnbfujns</p>
</section>

<style>
  .kennisclips {
    width: 90em;
    height: 42em;
    background-color: pink;
    margin: -0.5em;
    position: absolute;
    top: 1.5em;
  }

  section {
    opacity: 0;
    transform: translatex(42px);
    transition:
      opacity 0.5s ease-out,
      transform 1s ease-out;
    animation-duration: 4s;
  }

  section:target {
    opacity: 1;
    transform: translatex(0);
  }
</style>
