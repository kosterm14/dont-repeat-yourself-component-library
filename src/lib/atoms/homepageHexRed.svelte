<section class="red" />

<section class="h3-red">
	<h3>
		<em>Minicursussen</em>
	</h3>
	<img src="assets\arrows.svg" alt="">
</section>

<style>
	.red {
		background: var(--vtRed);

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

	.h3-red {
		color: var(--vtWhite);

		z-index: 1;
		display: grid;
		text-align: center;
		justify-items: center;
		align-content: center;
	}

	.red,
	.h3-red {
		grid-column-start: 5;
		grid-column-end: 7;
		grid-row-start: 3;

		margin-top: -10%;
	}

	em {
		font-family: var(--vtPrimaryFont);
		font-style: normal;

		font-size: 1rem;
	}

	@media (max-width: 31em) {
		.red,
		.h3-red {
			grid-column-start: 3;
            grid-column-end: 5;
            grid-row-start: 3;

			margin-top: -20%;
		}

		.red {
			width: 252px;
			height: 231px;
		}
	}
</style>
