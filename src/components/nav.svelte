<script>
	import image from '$lib/logo.png';
	import gh from '$lib/github-mark-white.png';
</script>

<div class="nav-container">
	<div class="thigngs">
		<img src={image} alt="hola" class="nav-img" />
		<p>Lorem</p>
		<p>Ipsum</p>
		<p>Dolor</p>
	</div>
	<img src={gh} alt="hola" class="nav-img" />
</div>

<style>
	.thigngs {
		display: flex;
		justify-content: center;
		align-items: center;
		gap: 100px;
	}
	.nav-container {
		height: 5rem;
		display: flex;
		justify-content: space-between;
		align-items: center;
		padding-inline: 10rem;
		background-color: #020202;
		border-bottom: 2px solid #cccccc;
	}
	.nav-img {
		height: 50px;
	}
	p {
		color: white;
	}
</style>
