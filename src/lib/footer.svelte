<script lang="ts">
    import { base } from '$app/paths';
</script>


<!-- This is an example component -->
<div class=" footer-bg">
	<div class="max-w-2xl mx-auto text-black py-10">
		<div class="text-center">
			<h3 class="text-3xl mb-3">Werde Teil der Picsel Plattform</h3>
			<p>Hier findest du unsere App.</p>
			<div class="flex flex-wrap justify-center my-10">
				<a href="https://play.google.com/store">
					<div class="flex items-center border w-56 rounded-lg px-4 py-2 w-52 mx-2 my-5">
						<img src="https://cdn-icons-png.flaticon.com/512/888/888857.png" class="w-7 md:w-8" />
						<div class="text-left ml-3">
							<p class="text-xs text-gray-800">Download on</p>
							<p class="text-sm md:text-base">Google Play Store</p>
						</div>
					</div>
				</a>
				<a href="https://www.apple.com/app-store/">
					<div class="flex items-center border w-56 rounded-lg px-4 py-2 w-44 my-5">
						<img src="https://cdn-icons-png.flaticon.com/512/888/888841.png" class="w-7 md:w-8" />
						<div class="text-left ml-3">
							<p class="text-xs text-gray-800">Download on</p>
							<p class="text-sm md:text-base">Apple Store</p>
						</div>
					</div>
				</a>
			</div>
		</div>
		<div class="mt-28 flex flex-col md:flex-row md:justify-between items-center text-sm text-black">
			<p class="order-2 md:order-1 mt-8 md:mt-0">&copy; Picsel, 2023.</p>
			<div class="order-1 md:order-2">
				<!-- <a class="px-2" href="{base}/contact">Kontakt</a> -->
				<a class="px-2 border-l" href="{base}/privacy">Datenschutz</a>
				<a class="px-2 border-l" href="{base}/agb">AGB</a>
			</div>
		</div>
	</div>
</div>

<style>
	.footer-bg {
		background: beige;
		background-size: cover;
	}
</style>
