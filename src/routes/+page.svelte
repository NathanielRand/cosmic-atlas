<script>
	import { Section, News, HeroHeader, HeroBody } from 'flowbite-svelte-blocks';
	import { Button } from 'flowbite-svelte';
	import { ArrowRightOutline } from 'flowbite-svelte-icons';

	// Image 
	import hero_planet from '$lib/assets/images/mars.jpg'
  </script>
  
<Section>
	<div class="w-full">
	  	<img src={hero_planet} alt="hero planet" />
	</div>
</Section>