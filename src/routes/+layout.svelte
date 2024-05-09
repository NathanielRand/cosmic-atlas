<script>
	import { Breadcrumb, BreadcrumbItem, DarkMode, Navbar, NavBrand, NavLi, NavUl, NavHamburger, Button, Input, Label } from 'flowbite-svelte';
	import { SearchOutline, HomeOutline } from 'flowbite-svelte-icons';
</script>
  
<Navbar class="bg-white dark:bg-black">
	<NavBrand href="/">
		<svg width="60" height="60" viewBox="0 0 192 192" xmlns="http://www.w3.org/2000/svg">
			<path fill="white" d="M96 148.084a53.43 53.43 0 0 0 37.17-14.959 2.096 2.096 0 0 0-2.902-3.022A49.25 49.25 0 0 1 96 143.895c-27.285 0-49.481-22.2-49.481-49.5s22.196-49.5 49.5-49.5c1.039 0 2.081.034 3.105.098a2.096 2.096 0 1 0 .259-4.181 54 54 0 0 0-3.375-.105c-29.595 0-53.67 24.075-53.67 53.67S66.405 148.084 96 148.084m46.781-37.511a50 50 0 0 1-3.041 6.998 2.093 2.093 0 0 0 .866 2.831 2.06 2.06 0 0 0 .979.247 2.09 2.09 0 0 0 1.853-1.125 53.6 53.6 0 0 0 3.304-7.594 2.096 2.096 0 1 0-3.96-1.369Zm4.53-8.791a2.096 2.096 0 0 0 2.081-1.875 55 55 0 0 0 .277-5.486 53.7 53.7 0 0 0-6.769-26.108 2.093 2.093 0 0 0-3.656 2.044 49.56 49.56 0 0 1 5.978 29.126 2.096 2.096 0 0 0 1.875 2.295 2 2 0 0 0 .214.004"/>
			<path fill="white" d="M164.565 141.071a82.5 82.5 0 0 0 14.359-46.657c0-45.724-37.2-82.924-82.924-82.924a82.95 82.95 0 0 0-40.973 10.811 2.096 2.096 0 1 0 2.074 3.641A78.7 78.7 0 0 1 96 15.679c43.414 0 78.75 35.321 78.75 78.75a78.3 78.3 0 0 1-13.631 44.295 2.096 2.096 0 1 0 3.461 2.362ZM47.085 30.026a2.096 2.096 0 0 0-2.948-.323 83 83 0 0 0-4.594 3.971 2.093 2.093 0 1 0 2.85 3.067 72 72 0 0 1 4.365-3.75 2.096 2.096 0 0 0 .326-2.966M96 177.337a83.4 83.4 0 0 0 18.862-2.152 2.096 2.096 0 0 0-.949-4.084 79.2 79.2 0 0 1-17.914 2.047c-43.414 0-78.75-35.321-78.75-78.75a78.15 78.15 0 0 1 15-46.2 2.096 2.096 0 1 0-3.375-2.449 82.3 82.3 0 0 0-15.799 48.664c0 45.724 37.2 82.924 82.924 82.924"/>
			<path fill="white" d="M73.961 89.302a2.096 2.096 0 1 0 4.08.949 18.428 18.428 0 1 1 1.369 12.206 2.093 2.093 0 1 0-3.75 1.834 22.52 22.52 0 0 0 15.244 12.161 22.8 22.8 0 0 0 5.156.596 22.628 22.628 0 1 0-22.084-27.75Zm87.72 71.573a19.654 19.654 0 1 0-19.65 19.65 19.676 19.676 0 0 0 19.65-19.65m-35.115 0a15.465 15.465 0 1 1 15.465 15.461 15.48 15.48 0 0 1-15.465-15.461M124.474 66a14.513 14.513 0 1 0-14.509-14.509A14.527 14.527 0 0 0 124.474 66m0-24.829a10.32 10.32 0 1 1-10.32 10.32 10.33 10.33 0 0 1 10.32-10.32"/>
		</svg>
		<span class="self-center whitespace-nowrap text-3xl font-thin dark:text-white ml-4">Cosmic Atlas</span>
	</NavBrand>
	<div class="p-4 h-24 w-3/4 flex justify-center">
		<Breadcrumb aria-label="Default breadcrumb example">
			<BreadcrumbItem>
				<svelte:fragment slot="icon">
					<HomeOutline class="w-4 h-4 me-2" />
			  	</svelte:fragment>
				Milky Way
			</BreadcrumbItem>
			<BreadcrumbItem>Sol</BreadcrumbItem>
			<BreadcrumbItem>Mars</BreadcrumbItem>
		</Breadcrumb>
		<Input id="large-input" size="lg" placeholder="Explore the Cosmos..." class="bg-white dark:bg-black w-full lg:w-2/3 ml-10" style="border-radius:25px;"/>
	</div>
	<div class="flex md:order-2">
		<Button color="none" data-collapse-toggle="mobile-menu-3" aria-controls="mobile-menu-3" aria-expanded="false" class="md:hidden text-gray-500 dark:text-gray-400 hover:bg-gray-100 dark:hover:bg-gray-700 focus:outline-none focus:ring-4 focus:ring-gray-200 dark:focus:ring-gray-700 rounded-lg text-sm p-2.5 me-1">
			<SearchOutline class="w-5 h-5" />
		</Button>
		<div class="hidden relative md:block">
			<DarkMode />
		</div>
		<NavHamburger />
	</div>
</Navbar>


<slot />