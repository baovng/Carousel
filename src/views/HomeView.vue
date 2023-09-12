<script setup></script>

<template>
	<div class="wrapper">
		<div
			id="carouselExampleIndicators"
			class="carousel slide carousel-fade"
			data-bs-ride="carousel"
			data-bs-touch="true"
			data-bs-interval="false"
		>
			<div class="carousel-indicators">
				<button
					type="button"
					data-bs-target="#carouselExampleIndicators"
					data-bs-slide-to="0"
					class="active"
					aria-current="true"
					aria-label="Slide 1"
				></button>
				<button
					type="button"
					data-bs-target="#carouselExampleIndicators"
					data-bs-slide-to="1"
					aria-label="Slide 2"
				></button>
				<button
					type="button"
					data-bs-target="#carouselExampleIndicators"
					data-bs-slide-to="2"
					aria-label="Slide 3"
				></button>
			</div>
			<div class="carousel-inner">
				<div class="carousel-item active item1"><div>First Slide</div></div>
				<div class="carousel-item item2"><div>Second Slide</div></div>
				<div class="carousel-item item3"><div>Thrid Slide</div></div>
			</div>
			<button
				class="carousel-control-prev"
				type="button"
				data-bs-target="#carouselExampleIndicators"
				data-bs-slide="prev"
			>
				<span class="carousel-control-prev-icon" aria-hidden="true"></span>
				<span class="visually-hidden">Previous</span>
			</button>
			<button
				class="carousel-control-next"
				type="button"
				data-bs-target="#carouselExampleIndicators"
				data-bs-slide="next"
			>
				<span class="carousel-control-next-icon" aria-hidden="true"></span>
				<span class="visually-hidden">Next</span>
			</button>
		</div>
	</div>
</template>

<style>
	.wrapper {
		height: 100vh;
		width: 100vw;
	}
	.carousel-item {
		display: flex !important;
		justify-content: center;
		align-items: center;
		font-size: 50px;
		font-family: 'Courier New', Courier, monospace;
		text-transform: uppercase;
		color: rgb(236, 236, 236);
		font-weight: 500;
		letter-spacing: 5px;
	}
	.item1,
	.item2,
	.item3 {
		background-size: cover;
		background-position: center;
		background-repeat: no-repeat;
		background-position-y: center;
		height: 100vh;
		max-height: 100vh;
	}
	.item1 {
		background-image: url('../assets/1.jpg');
	}
	.item2 {
		background-image: url('../assets/2.jpg');
	}
	.item3 {
		background-image: url('../assets/3.jpg');
	}
</style>
