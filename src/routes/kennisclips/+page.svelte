<script>
  import Header from "../../lib/components/header.svelte";
  let backgroundImage = "url(Rn7scw.gif)";
</script>

<Header />

<section style="background-image: {backgroundImage};">
  <h1>Onderzoeken en begrijpen</h1>

  <p>
    De wereld wordt steeds complexer en het maken van tekeningen kan helpen bij
    het begrijpen en overbrengen van ideeën. Visual thinking wordt in het
    bedrijfsleven steeds meer toegepast maar voor de praktijk van het hoger
    onderwijs vormt het nog een uitdaging. Het is nog niet zo gewoon om als
    docent (live) te tekenen tijdens het geven van de les of om als student
    visuele aantekeningen te maken (sketchnotes).
  </p>

  <p>
    En dit terwijl het aantoonbaar gunstig is om studenten zelf te laten
    tekenen. Zo kunnen ze zich beter concentreren en worden er meerdere
    zintuigen tegelijk geprikkeld. Naast het verhogen van de participatie wordt
    het ook voor de docent een stuk inzichtelijker wie er actief meedoet aan de
    les en wat er van de stof begrepen wordt. De docent kan de sketchnotes
    tijdens of na de les bekijken en daar weer vragen over stellen.
  </p>

  <p>
    Waar je bij geschreven tekst gemakkelijk een hele zin of woord kunt
    overschrijven zonder daadwerkelijk te begrijpen waar het over gaat, is dat
    bij het maken van visuele aantekeningen veel moeilijker. Andersom hoef je de
    taal niet volledig meester te zijn om toch aan te tonen dat je een bepaalde
    term wel begrijpt. In de kennisclip wordt uitgelegd hoe visual thinking
    studenten de lesstof beter laat begrijpen en hoe de werkvormen op het
    platform hierbij kunnen helpen.
  </p>
</section>

<style>
  section {
    padding: 3em;
    margin: -1em;
    background-repeat: no-repeat;
    background-position-x: 58em;
    background-position-y: 4em;
    background-size: 23vw;
  }

  h1 {
    font-family: var(--vtPrimaryFont);
    color: var(--vtDarkBlue);
  }

  p {
    line-height: 1.5em;
    font-size: 17px;
    font-family: var(--vtSecondaryFont);
    width: 41vw;
  }
</style>
