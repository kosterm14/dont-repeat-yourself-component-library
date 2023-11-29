<section class="blue" />

<section class="h3-blue">
    <h3>
        <em>Over <br /> visual thinking</em>
    </h3>
    <img src="assets\arrows.svg" alt="">
</section>

<style>
    .blue {
        background: var(--vtSec-DarkBlue);

        width: 300px;
        height: 275px;
        clip-path: polygon(
            25% 0%,
            75% 0%,
            100% 50%,
            75% 100%,
            25% 100%,
            0% 50%
        );
        transform: rotate(90deg);
    }

    .h3-blue {
        color: var(--vtWhite);

        z-index: 1;
        display: grid;
        text-align: center;
        justify-items: center;
        align-content: center;
    }

    .blue,
    .h3-blue {
        grid-column-start: 2;
        grid-column-end: 4;
        grid-row-start: 2;

        margin-top: -7%;
    }

    em {
        font-family: var(--vtPrimaryFont);
        font-style: normal;

        font-size: 1rem;
    }

    @media (max-width: 31em) {
        .blue,
        .h3-blue {
            grid-column-start: 2;
            grid-column-end: 4;
            grid-row-start: 2;

            margin-bottom: 15%;
        }

        .blue {
            width: 252px;
            height: 231px;
        }
    }
</style>
