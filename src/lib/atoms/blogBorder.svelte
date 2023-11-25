<section>
  <div class="cards">
    <section class="cardyellow" />
    <section class="cardscolordarkblue" />
    <section class="cardyellow" />
    <section class="cardscolordarkblue" />
    <section class="cardyellow" />
    <section class="cardscolordarkblue" />
  </div>
</section>

<style>
  .cardscolordarkblue {
    width: 14em;
    height: 20em;
    border-radius: 2%;
    border: 3px solid var(--vtDarkBlue);
    padding: 0.6em;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  }

  .cardyellow {
    width: 14em;
    height: 20em;
    border-radius: 2%;
    border: 3px solid var(--vtYellow);
    padding: 0.6em;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  }

  .cards {
    display: grid;
    grid-template-columns: 1fr 1fr 4fr;
    justify-content: center;
    align-items: center;
    gap: 5em;
  }
</style>
