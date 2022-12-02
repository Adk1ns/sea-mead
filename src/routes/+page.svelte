<script>
	import pour from '../lib/images/pour.jpg';
	import barrels from '../lib/images/barrels.jpg';
	import HomeTop from '../components/original.svelte/homeTop.svelte';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<div class="parallax">
		<div class="d-flex justify-content-center pt-5">
			<h1 class="playball title">Sea Mead</h1>
		</div>
		<div class="d-flex justify-content-center">
			<h1 class="playball title-sub">Premium Honey Wine</h1>
		</div>
	</div>

	<div class="row g-0 inside-nav">
		<div class="d-flex justify-content-around crimson-pro">
			<p>Home</p>
			<p>Shop</p>
		</div>
	</div>
	<!-- make a div here that will host the home/away/shop PAGES -->
	<!-- beige background, PAGES can fade in and out over -->
	<!-- after this do something about the footer -->
	<div class="row g-0">
		<div class="col-6 info-left p-5 crimson-pro text-center ">
			<HomeTop />
		</div>
		<div class="col-6 image-right">
			<div class="container-img">
				<div class="pour-img" />
			</div>
		</div>
	</div>

	<div class="row g-0">
		<div class="col-6 image-right">
			<div class="container-img">
				<div class="barrel-img" />
			</div>
		</div>
		<div class="col-6 info-left p-5 crimson-pro text-center">
			<HomeTop />
		</div>
	</div>
	<!-- end here -->

	<footer class="footer d-flex justify-content-center crimson-pro">
		<p class="my-2 text-white">Sea Mead, 2022</p>
	</footer>
</section>

<style>
	.parallax {
		background-image: url('src/lib/images/meadRow.jpg');
		min-height: 500px;
		width: 100%;
		/* Create the parallax scrolling effect */
		background-attachment: fixed;
		background-position: center;
		background-repeat: no-repeat;
		background-size: cover;
	}
	.info-left {
		background-color: #fdeed9;
	}
	.image-right {
		background-color: #fdeed9;
	}
	.container-img {
		width: 100%;
	}
	.pour-img {
		background-image: url('src/lib/images/pour.jpg');
		background-attachment: fixed;
		background-position: right;
		background-repeat: no-repeat;
		background-size: 70%;
		object-fit: cover;
		object-position: 100%;
		width: 100%;
		aspect-ratio: 1/1;
	}
	.barrel-img {
		background-image: url('src/lib/images/barrels.jpg');
		background-attachment: fixed;
		background-position: center;
		background-repeat: no-repeat;
		object-fit: cover;
		object-position: 100%;
		width: 100%;
		aspect-ratio: 1/1;
	}
	.title {
		color: white;
		font-size: 10em;
		position: relative;
		top: 50%;
	}
	.title-sub {
		color: white;
		font-size: 2em;
	}
	.inside-nav {
		background-color: black;
		color: white;
		height: 3rem;
	}
	p {
		font-size: 2em;
	}
	.footer {
		background-color: black;
	}
</style>
