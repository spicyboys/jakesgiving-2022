<script>
	import '../app.css';
</script>

<div
	class="wrapper h-screen bg-[#0A4B5E] static grid overflow-hidden overflow-y-scroll bg-no-repeat bg-center"
>
	<slot />
</div>

<style lang="postcss">
	.wrapper {
		background-image: url(/wreath.svg);
		background-size: max(125vw, 125vh);
	}
</style>
