<script>
	import { Section } from 'flowbite-svelte-blocks';
	import { Button, Hr } from 'flowbite-svelte';
	import { ArrowRightOutline } from 'flowbite-svelte-icons';

	// Image 
	import hero_planet from '$lib/assets/images/mars.jpg'
  </script>
  
<Section>
	<div class="grid grid-cols-12 gap-4">
		<div class="col-span-9">
			<img src={hero_planet} alt="hero planet" />
		</div>
		<div class="col-span-3">
			<div class="border border-2 rounded-xl w-full p-4">
				<p class="text-gray-400 font-thin">Planet</p>
				<h1 class="font-bold text-4xl dark:text-white">Mars</h1>
				<p class="text-gray-400 font-thin mt-4">System</p>
				<h2 class="font-bold text-2xl dark:text-white">Sol</h2>
				<p class="text-gray-400 font-thin mt-2">Galaxy</p>
				<h3 class="font-bold text-2xl dark:text-white">Milky Way</h3>
				<Hr />
				<ul class="dark:text-white">
					<li>Coordinates: RA 0h 29m 15s | Dec +1° 46′ 52″</li>
					<li>Moons: <a href="#">Phobos</a></li>
					<li>Moons: <a href="#">Deimos</a></li>
					<li>Orbital Period: 687 days</li>
					<li>Diameter: 1,275 km</li>
					<li>Radius: 2,106.1 mi</li>
					<li>Mass: 0.10643</li>
					<li>Length of day: 1d 0h 37m</li>
					<li>Distance from Sun: 141.6 million mi</li>
				</ul>
			</div>
		</div>		
	</div>
</Section>

<Section>
	<div class="container mx-auto px-8">
		<h2 class="font-bold text-4xl dark:text-white">Solar System</h2>
		<p class="text-gray-400 font-thin mt-2">The Solar System is the gravitationally bound system of the Sun and the objects that orbit it, either directly or indirectly. It includes the planets, dwarf planets, moons, asteroids, and comets in our solar system.</p>
		<div class="flex flex-wrap">
			<div class="w-full md:w-1/2 lg:w-1/3 px-4 py-6">
				<h3 class="font-bold text-xl dark:text-white">Mercury</h3>
				<p class="text-gray-400 font-thin mt-2">Mercury is the smallest and innermost planet in the Solar System. Its orbital period around the Sun of 87.969 days is the shortest of all the planets in the Solar System.</p>
			</div>
			<div class="w-full md:w-1/2 lg:w-1/3 px-4 py-6">
				<h3 class="font-bold text-xl dark:text-white">Venus</h3>
				<p class="text-gray-400 font-thin mt-2">Venus is the second planet from the Sun. It is named after the Roman goddess of love and beauty.</p>
			</div>
			<div class="w-full md:w-1/2 lg:w-1/3 px-4 py-6">
				<h3 class="font-bold text-xl dark:text-white">Earth</h3>
				<p class="text-gray-400 font-thin mt-2">Earth is the third planet from the Sun and the only object in the Solar System visible to the naked eye.</p>
			</div>
		</div>
	</div>
</Section>