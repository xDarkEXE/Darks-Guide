<script lang="ts">
	import "../app.pcss"
	import { page } from "$app/stores";

	$: activeUrl = $page.url.pathname;

	import { Button } from "flowbite-svelte"
	import { ChevronDownOutline } from "flowbite-svelte-icons";
</script>

<svelte:head>
	<title>Dark's GameGuide</title>
	<link rel="preconnect" href="https://fonts.googleapis.com">
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
	<link href="https://fonts.googleapis.com/css2?family=Lexend+Deca:wght@100..900&display=swap" rel="stylesheet">
</svelte:head>

<div class="h-screen flex flex-col">
	<nav class="w-full p-5 justify-start items-start gap-[100px] inline-flex">
		<div class="justify-start items-center gap-[25px] inline-flex grow">
			<h1 class="scroll-m-20 text-2xl font-semibold tracking-tight xl:text-4xl">
				Dark's GameGuide
			</h1>
			<div class="p-2.5 justify-start items-center gap-1 inline-flex">
				<Button href="/" class="leading-7">
					Home
				</Button>
				<Button href="/Left4Dead" class="ms-2">
					Left 4 Dead Guide
				</Button>
			</div>
		</div>
	</nav>
	<slot></slot>
</div>