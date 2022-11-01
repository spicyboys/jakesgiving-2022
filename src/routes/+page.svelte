<script lang="ts">
	import { PUBLIC_STREET_ADDRESS, PUBLIC_CITY_STATE_ZIP } from '$env/static/public';
</script>

<div class="text-center self-center">
	<p class="text-[#F4EBD0] text-2xl sm:text-4xl pb-4 italic">Join us for the 10th annual</p>

	<h1 class="text-[#CEB745] text-4xl sm:text-8xl">
		JAKESGIVING
		<br />
		DINNER
	</h1>

	<div class="text-[#F4EBD0] text-2xl pt-8">
		<p>Saturday, November 19<sup>th</sup> @ 8 PM</p>
		<p>{PUBLIC_STREET_ADDRESS}</p>
		<p>{PUBLIC_CITY_STATE_ZIP}</p>
	</div>

	<div class="pt-4 inline-flex space-x-0 sm:space-x-2 space-y-2 sm:space-y-0 sm:flex-row flex-col">
		<a href="/menu" class="link">Menu</a>
		<a href="https://forms.gle/mE2Ve7VdRzZeakNZ6" class="link" rel="noreferrer nofollow">RSVP</a>
		<a href="/faqs" class="link">FAQs</a>
	</div>
</div>

<style lang="postcss">
	h1 {
		font-family: 'Abril Fatface', cursive;
	}

	:global(body) {
		font-family: 'Aleo', serif;
	}

	a.link {
		@apply w-40 h-10 flex items-center justify-center rounded-md bg-[#F4EBD0] text-black mx-auto text-lg;
	}
</style>
