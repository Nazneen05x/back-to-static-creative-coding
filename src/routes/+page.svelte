<script>
  import Footer from "../lib/components/footer.svelte";
  import Header from "../lib/components/header.svelte";
  import Kennisclips from "../lib/components/kennisclips.svelte";
  import Overons from "../lib/components/overons.svelte";
</script>

<Header />

<main>
  <Overons />
  <Kennisclips />
</main>

<!-- <Footer /> -->

<style>
  main {
    position: relative;
  }
</style>
