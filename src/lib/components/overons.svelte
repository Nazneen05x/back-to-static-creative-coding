<section id="overons" class="overons">
  <h1>hoiu</h1>
  <p>hydunjshbfyusjnbfujns</p>
</section>

<section class="slide" onclick="toggleSlide()"></section>

<style>
  .slide {
    width: 90em;
    height: 42em;
    background-color: aquamarine;
    margin: -0.5em;
    position: absolute;
    top: 1.5em;
  }

  .slide {
    opacity: 0;
    transform: translatex(42px);
    transition:
      opacity 0.5s ease-in-out,
      transform 0.5s ease-in-out;
  }

  .slide {
    opacity: 1;
    transform: translatex(0);
  }
</style>
