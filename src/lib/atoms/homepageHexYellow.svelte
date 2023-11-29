<section class="yellow" />

<section class="h3-yellow">
	<a href="/tekenmethodes">
		<h3>
			<em>Ontdek de <br />visual thinking <br /> methodes</em>
		</h3>
		<img src="assets\arrows.svg" alt="">
	</a>
</section>

<style>
	.yellow {
		background: var(--vtYellow);

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

	.h3-yellow {
		color: var(--vtWhite);

		z-index: 1;
		display: grid;
		text-align: center;
		justify-items: center;
		align-content: center;
	}

	.yellow,
	.h3-yellow {
		grid-column-start: 6;
		grid-column-end: 8;
		grid-row-start: 2;

		margin-top: -7%;
	}

	a {
		text-decoration: none;
		cursor: pointer;
		color: var(--vtWhite);
	}

	em {
		font-family: var(--vtPrimaryFont);
		font-style: normal;

		font-size: 1rem;
	}

	@media (max-width: 31em) {
		.yellow,
		.h3-yellow {
			grid-column-start: 2;
            grid-column-end: 4;
            grid-row-start: 4;

			margin-bottom: 15%;
		}

		.yellow {
			width: 252px;
			height: 231px;
		}
	}
</style>
