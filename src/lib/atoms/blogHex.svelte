<!-- <div class="grid-container2">
  <section class="yellow2-1">
    <section class="white2-1" />
  </section>

  <section class="h3-yellow2-1">
    <h3>
      <em>Onderzoeken <br /> en begrijpen</em>
    </h3>
  </section>

  <section class="yellow2-2">
    <section class="white2-2" />
  </section>
</div> -->

<style>
  .grid-container2 {
    display: grid;
    grid-template-columns: auto;
    margin-top: 15%;
    justify-content: center;
  }

  .yellow2-1,
  .h3-yellow2-1 {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 2;
  }

  .yellow2-2,
  .h3-yellow2-2 {
    grid-column-start: 3;
    grid-column-end: 5;
    grid-row-start: 2;
  }

  .white2-1,
  .white2-2,
  .yellow2-1,
  .yellow2-2 {
    z-index: 1;
    display: grid;
    text-align: center;
    justify-items: center;
    align-content: center;
    clip-path: polygon(25% 0%, 75% 0%, 100% 50%, 75% 100%, 25% 100%, 0% 50%);
    transform: rotate(90deg);
  }

  .white2-1,
  .white2-2 {
    width: calc(285px);
    height: calc(261.25px);
    background-color: white;
    transform: rotate(0deg);
  }

  .yellow2-1,
  .yellow2-2 {
    width: 300px;
    height: 275px;
    background: var(--vtYellow);
  }
</style>
