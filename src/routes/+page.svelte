<script>
	import { Section, Social } from 'flowbite-svelte-blocks';
	import { Button, Hr, Badge } from 'flowbite-svelte';
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
				<p class="text-gray-400 font-thin mt-6">Coordinates</p>
				<h3 class="font-bold dark:text-gray-100">RA 0h 29m 15s | Dec +1° 46′ 52″</h3>
				<Hr />
				<ul class="dark:text-white">
					<li>Moons: <a href="#">Phobos</a></li>
					<li>Moons: <a href="#">Deimos</a></li>
					<li class="mb-2"><Badge color="yellow">Habitability: 60%</Badge></li>
					
					<p class="text-gray-400 text-2xl font-thin my-4">Atmosphere</p>
					<li>
						<div class="flex">
							<div class="w-1/2">
								<ul>
									<li>Carbon: 96.0%</li>
									<li>Nitrogen: 2.1%</li>
									<li>Argon: 1.9%</li>
									<li>Oxygen: 0.145%</li>
								</ul>
							</div>
							<div class="w-1/2">
								<ul>
									<li>Carbon Monoxide: >0%</li>
									<li>Water: >0%</li>
									<li>Methane: >0%</li>
									<li>Gases: >0%</li>
								</ul>
							</div>
						</div>
					</li>
				</ul>
			</div>
		</div>		
	</div>
	<hr class="w-2/5 mx-auto"/>
	<Social>
		<div class="flex flex-col items-center justify-center  border-b rounded-xl p-4">
			<dt class="mb-2 text-3xl md:text-4xl font-extrabold">-65°<small>C</small></dt>
			<dd class="font-light text-gray-500 dark:text-gray-400">temperature</dd>
		</div>
		<div class="flex flex-col items-center justify-center  border-b rounded-xl p-4">
			<dt class="mb-2 text-3xl md:text-4xl font-extrabold">14%</dt>
			<dd class="font-light text-gray-500 dark:text-gray-400">water</dd>
		</div>
		<div class="flex flex-col items-center justify-center border-b rounded-xl p-4">
			<dt class="mb-2 text-3xl md:text-4xl font-extrabold">Solar</dt>
			<dd class="font-light text-gray-500 dark:text-gray-400">energy</dd>
		</div>
		<div class="flex gap-4">
			<div class="w-full flex flex-col items-center text-center justify-center border-b rounded-xl p-4">
				<dt class="mb-2 text-3xl md:text-xl font-extrabold">20°C - -153°C</dt>
				<dd class="font-light text-gray-500 dark:text-gray-400">temperature range</dd>
			</div>
		</div>
		<div class="flex flex-col items-center justify-center  border-b rounded-xl p-4">
			<dt class="mb-2 text-3xl md:text-4xl font-extrabold">1<small>d</small> 0<small>h</small> 37<small>m</small></dt>
			<dd class="font-light text-gray-500 dark:text-gray-400">Length of Day</dd>
		</div>
		<div class="flex flex-col items-center justify-center  border-b rounded-xl p-4">
			<dt class="mb-2 text-3xl md:text-4xl font-extrabold">687<small>days</small></dt>
			<dd class="font-light text-gray-500 dark:text-gray-400">Orbital Period</dd>
		</div>
		<div class="flex flex-col items-center justify-center border-b rounded-xl p-4">
			<dt class="mb-2 text-3xl md:text-4xl font-extrabold">1,275 <small class="text-sm">km</small></dt>
			<dd class="font-light text-gray-500 dark:text-gray-400">Diameter</dd>
		</div>
		<div class="flex flex-col items-center justify-center  border-b rounded-xl p-4">
			<dt class="mb-2 text-3xl md:text-3xl font-extrabold">6.42 x 1023 <small class="text-sm">kg</small></dt>
			<dd class="font-light text-gray-500 dark:text-gray-400">Mass</dd>
		</div>
		<div class="flex flex-col items-center justify-center  border-b rounded-xl p-4">
			<dt class="mb-2 text-3xl md:text-4xl font-extrabold">228 <small class="text-sm">mil km</small></dt>
			<dd class="font-light text-gray-500 dark:text-gray-400">Distance from Sun</dd>
		</div>
		<div class="flex flex-col items-center justify-center  border-b rounded-xl p-4">
			<dt class="mb-2 text-3xl md:text-4xl font-extrabold">≈0.020 <small class="text-sm">kg/m3</small></dt>
			<dd class="font-light text-gray-500 dark:text-gray-400">Atmosphere</dd>
		</div>
		<div class="flex flex-col items-center justify-center  border-b rounded-xl p-4">
			<dt class="mb-2 text-3xl md:text-4xl font-extrabold">0%</dt>
			<dd class="font-light text-gray-500 dark:text-gray-400">Terraforming</dd>
		</div>
	</Social>
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