<section class="gray2" />

<section class="h3-gray2">
    <a href="/tekenruimte">
        <h3>
            <em>Tekenruimte</em>
        </h3>
        <img src="assets\arrows_black.svg" alt="">
    </a>
</section>

<style>
    .gray2 {
        background: var(--vtGrey-50);

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

    .h3-gray2 {
        color: var(--vtDarkBlue);

        z-index: 1;
        display: grid;
        text-align: center;
        justify-items: center;
        align-content: center;
    }

    .gray2,
    .h3-gray2 {
        grid-column-start: 7;
        grid-column-end: 9;
        grid-row-start: 3;

        margin-top: -10%;
    }

    a {
        color: var(--vtDarkBlue);

        text-decoration: none;
        cursor: pointer;
    }

    em {
        font-family: var(--vtPrimaryFont);
        font-style: normal;

        font-size: 1rem;
    }

    @media (max-width: 31em) {
        .gray2,
        .h3-gray2 {
            grid-column-start: 1;
            grid-column-end: 3;
            grid-row-start: 5;

            margin-top: -20%;
        }

        .gray2 {
            width: 252px;
            height: 231px;
        }
    }
</style>
