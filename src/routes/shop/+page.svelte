<script>

</script>


<section>
	<div class="parallax top">
		<div class="d-flex justify-content-center pt-5">
			<h1 class="playball title">Sea Mead</h1>
		</div>
		<div class="d-flex justify-content-center">
			<h1 class="playball title-sub">Premium Honey Wine</h1>
		</div>
	</div>

	<div class="row g-0 inside-nav">
		<nav class="d-flex justify-content-around crimson-pro">
			<a href="/">Home</a>
			<a href="/shop">Shop</a>
		</nav>
	</div>
	<!-- make a div here that will host the home/away/shop PAGES -->
	<!-- beige background, PAGES can fade in and out over -->
	<!-- after this do something about the footer -->
    <div class='shop'>
        <h1>Open 2025</h1>
        <div class="divider-line mx-auto my-2 my-lg-4" />
        <h5>Our current production facility is not commercially licensed at this time.</h5>
        <div class="divider-line mx-auto my-2 my-lg-4" />
        <h5>We cater exclusively to friends, family, and private parties.</h5>
        <h5>For more info contact: jeredkins@gmail.com</h5>
    </div>

	<!-- end here -->

	<footer class="footer d-flex justify-content-center crimson-pro">
		<p class="my-2 text-white">Sea Mead, 2023</p>
	</footer>
</section>

<style lang='css'>
	.parallax {
		background-image: url('src/lib/images/meadRow.jpg');

		width: 100%;
		/* Create the parallax scrolling effect */
		background-attachment: fixed;
		background-position: center;
		background-repeat: no-repeat;
		background-size: cover;
	}

    .divider-line {
		border-bottom: 1px solid black;
		width: 80%;
	}

	.top {
		height: 50vh;
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
	a {
		color: white;
		font-size: 2em;
		text-decoration: none;
	}
    .shop {
        background-color: #fdeed9;
        width: 100%;
        height: 50vh;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        font-family: Crimson-pro;
    }


	.footer {
		background-color: black;
		width: 100%;
	}
	@media (max-width: 868px) {

	}
	@media (max-width: 575px) {

	}

	
</style>
