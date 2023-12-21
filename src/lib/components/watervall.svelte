<!-- IMG - GRASS -->
<section class="green">
  <img class="grass"   src="/grass.png" alt="grass" />
</section>

<!-- IMG - MOND -->
<section class="mond">
  <img src="/mond.jpg" alt="mond" >
</section>

<!-- BERG - MOUNTAIN -->
<section class="berg"></section>
<section class="berg1"></section>

<!-- WATER - ZEE -->
<section class="water"></section>

<!-- STEEN - ROTSEN -->
<section class="rots"></section>
<section class="rots1"></section>
<section class="rots2"></section>
<section class="rots3"></section>
<section class="rots4"></section>

<!-- BUBBLEGUM ANIMATION -->
<section class="bubblegum">
  <section></section>
  <section></section>
  <section></section>
  <section></section>
  <section></section>
  <section></section>
  <section></section>
  <section></section>
  <section></section>
</section>


<style>
  .water {
    background-color: skyblue;
    width: 101vw;
    height: 20em;
    margin: -1em;
    position: relative;
    bottom: -30em;
  }

  

  .berg {
    width: 38vw;
    height: 30em;
    background-color: #a17a74;
    position: absolute;
    margin: 0em;
    margin-left: -1em;
    border-top-right-radius: 13em;
    background: linear-gradient(to right, #a17a74, rgba(87, 87, 87, 0.5)),
      url(https://1.bp.blogspot.com/-Zoy_zOte-Pk/VfcVS2lkK9I/AAAAAAAAIGM/SLV5Cs2Ajmc/s1600/Dark%2Bmountain%2Btexture%2Bsep.jpg);
  }

  .berg1 {
    width: 38vw;
    height: 30em;
    background-color: #a17a74;
    position: absolute;
    margin: 0em;
    margin-left: 56em;
    border-top-left-radius: 13em;
    background: linear-gradient(to left, #a17a74, rgba(87, 87, 87, 0.5)),
      url(https://1.bp.blogspot.com/-Zoy_zOte-Pk/VfcVS2lkK9I/AAAAAAAAIGM/SLV5Cs2Ajmc/s1600/Dark%2Bmountain%2Btexture%2Bsep.jpg);
  }

  .rots {
    background-color: gray;
    width: 14vw;
    height: 7em;
    border-top-left-radius: 9em;
    border-top-right-radius: 13em;
    position: relative;
    top: 4em;
    left: 9em;
    background: linear-gradient(to right, #3f3f41, rgba(87, 87, 87, 0.5)),
      url(https://grainy-gradients.vercel.app/noise.svg);
  }

  .grass {
    width: 6vw;
    position: absolute;
    margin-top: 25.5em;
    margin-left: 6em;
    z-index: 1;
  }

  .mond{
    width: 24vw;
    position: absolute;
    margin-top: -9em;
    margin-left: 25em;
  }

  .rots1 {
    background-color: darkgray;
    width: 4vw;
    height: 2em;
    border-top-left-radius: 14em;
    border-top-right-radius: 13em;
    position: relative;
    top: 2em;
    left: 19em;
    background: linear-gradient(to left, #888888, rgba(3, 3, 3, 0.358)),
      url(https://grainy-gradients.vercel.app/noise.svg);
  }

  .rots2 {
    background-color: darkgray;
    width: 6vw;
    height: 3em;
    border-top-left-radius: 25em;
    border-top-right-radius: 26em;
    position: relative;
    top: -1em;
    left: 3em;
    background: linear-gradient(to left, #888888, rgba(3, 3, 3, 0.358)),
      url(https://grainy-gradients.vercel.app/noise.svg);
  }

  .rots3 {
    background-color: darkgray;
    width: 6vw;
    height: 3em;
    border-top-left-radius: 25em;
    border-top-right-radius: 26em;
    position: relative;
    top: 7em;
    left: 57em;
    background: linear-gradient(to left, #888888, rgba(3, 3, 3, 0.358)),
      url(https://grainy-gradients.vercel.app/noise.svg);
  }

  .rots4 {
    background-color: gray;
    width: 14vw;
    height: 7em;
    border-top-left-radius: 9em;
    border-top-right-radius: 13em;
    position: relative;
    top: 0em;
    left: 59em;
    background: linear-gradient(to right, #3f3f41, rgba(87, 87, 87, 0.5)),
      url(https://grainy-gradients.vercel.app/noise.svg);
  }

  /* BUBBLEGUM  */
  .bubblegum{
    position: absolute;
    top:0;
    left: 41em;
    width: 100%;
    height: 100%;
    overflow: hidden;
  }

  @keyframes bubble {
    0%{
      opacity: 1;
      transform: translateY(0) rotate(0deg);
    }

    100%{
       opacity: 0;
      border-radius: 50%; 
      transform: translateY(1000px) rotate(720deg);
    }
  }

  .bubblegum section{
    width: 100px;
    height: 100px;
    border-radius: 50%;
    background-color: pink;
    top: 0em;
    animation: bubble 10s linear  infinite;
  }

.bubblegum section:nth-child(1) {
	left: 25%;
	width: 80px;
	height: 80px;
	animation-delay: 0s;
}

.bubblegum section:nth-child(2) {
	right: 10%;
	width: 20px;
	height: 20px;
	animation-delay: 2s;
	animation-duration: 12s;
}

.bubblegum section:nth-child(3) {
	left: 70%;
	width: 20px;
	height: 20px;
	animation-delay: 4s;
}

.bubblegum section:nth-child(4) {
	right: 40%;
	width: 60px;
	height: 60px;
	animation-delay: 0s;
	animation-duration: 18s;
}

.bubblegum section:nth-child(5) {
	left: 65%;
	width: 20px;
	height: 20px;
	animation-delay: 0s;
}

.bubblegum section:nth-child(6) {
	right: 75%;
	width: 110px;
	height: 110px;
	animation-delay: 3s;
}
</style>
