<script>
	import Nav from '../components/nav.svelte';
</script>

<Nav />
<div class="title-container">
	<h1 class="title">
		Shorten your links
		<span>
			like
			<span class="title-gradient">never before</span>
		</span>
	</h1>
	<h2 class="subtitle">
		Track your users. Track the wanted.<br />Get going with just a link. We'll handle the rest
	</h2>
	<div class="button-container">
		<button class="get-started">Get Started</button>
		<button class="learn-more">Learn More</button>
	</div>
</div>
<div style="background-color: white; display: flex; width: 100%">
	<h1>More content here...</h1>
</div>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;700;800&family=Inter:wght@300&display=swap');
	.title-container {
		padding-top: 4rem;
		height: 80vh;
		background-color: #020202;
		display: flex;
		flex-direction: column;
		align-items: center;
		gap: 40px;
	}
	.title {
		text-align: center;
		width: 1000px;
		font-size: 6rem;
		font-family: Inter;
		color: #fbfbfb;
		font-weight: 700;
	}
	.title-gradient {
		/* display: inline-block; */
		color: transparent;
		--bg: linear-gradient(90deg, #8bdeda 0%, #43add0 25%, #998ee0 50%, #e17dc2 75%, #ef9393 100%);

		background:
			var(--bg),
			var(--bg) bottom 5px left 0/100% 5px no-repeat;
		background-clip: text, padding-box;
		-webkit-background-clip: text, padding-box;

		font-family: Inter;
		padding-right: 10px;
		font-size: 6rem;
		font-style: italic;
		font-weight: 900;
		line-height: 110%;
		display: inline-block; /* Fix clipping issue */
		text-decoration: underline; /* Apply underline */
	}
	.subtitle {
		text-align: center;
		color: #fbfbfb;
		padding-top: 0.5rem;
		font-family: Inter;
		font-weight: 600;
		font-size: 1.8rem;
	}
	.button-container {
		padding: 2.5rem;
		display: flex;
		gap: 100px;
	}
	.learn-more {
		width: 180px;
		height: 46px;
		color: white;
		border: none;
		border-radius: 5px;
		background: transparent;
		border: 2px solid white;
		text-align: center;
		font-family: Inter;
		font-size: 16px;
		font-style: normal;
		font-weight: 500;
	}
	.get-started {
		width: 180px;
		height: 46px;
		background: linear-gradient(90deg, #4ac7fa 0.01%, #e649f5 131.69%);
		color: white;
		border: none;
		border-radius: 5px;
		text-align: center;
		font-family: Inter;
		font-size: 16px;
		font-style: normal;
		font-weight: 500;
	}
</style>
