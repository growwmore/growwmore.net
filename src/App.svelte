<script>
	export let name;
</script>

<main>
	<h1>“Investing is for Everyone.<br><span class="h1title">Growwmore</span> is here to guide you.”</h1>
	<br><br>
	<h3>A venture by <span class="h3title">Raj Chhaniyara</span> & <span class="h3title">Raj Patel</span></h3>
	<!-- <address style="color:#d31c3a">Reach us at <a href="mailto:hello@growwmore.net">hello@growwmore.net</a>.</address> -->
</main>

<style>
	@font-face {
		font-family: 'IntroCap';
		src: url('/static/fonts/IntroCapsCd-Trial-BkInl.ttf');
	}

	@font-face {
		font-family: 'IntroNor';
		src: url('/static/fonts/IntroHeadR-Base.otf');
	}

	main {
		text-align: center;
		padding: 12em;
		max-width: 300px;
		margin: 0 auto;
	}

	/* If you want the content centered horizontally and vertically */
	.centered {
		position: absolute;
		top: 50%;
		left: 50%;
		transform: translate(-50%, -50%);
		text-align: center;
	}

	#bottom {
		position: absolute;
		bottom: 0;
		left: 0;
	}

	h1 {
		color: #0035ff;
		font-family: "IntroCap", Times, serif;
		font-size: 5em;
		font-weight: 100;
		margin: 0 auto;
	}

	.h1title {
		color: #ff0026;
	}

	h3 {
		color: #9c9c9c;
		font-family: "IntroNor", Times, serif;
		font-size: 2em;
		font-weight: 100;
		text-transform: uppercase;
		margin: 0 auto;
	}

	.h3title {
		color: #212121;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>