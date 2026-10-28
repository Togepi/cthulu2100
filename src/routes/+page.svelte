<script lang="ts">
	import bg_video from '#lib/assets/hero_bg.webm';
</script>

<video autoplay muted loop id="myVideo" class="fixed inset-0 z-10 h-full w-full object-cover">
	<source src={bg_video} type="video/mp4" class="h-full w-full" />
</video>

<main
	class="fixed z-10 flex h-dvh w-dvw flex-col items-center justify-center text-center font-semibold text-cyan-500"
>
	<h1 class="font-kyrios text-6xl text-cyan-500 md:text-9xl">CTHULU 2100</h1>
	<p class="font-kyrios text-4xl">Jeu de rôle grandeur nature</p>
	<p class="mt-8">25-26 Février 2028</p>
	<p>Domaine de Monteret à Saint-Cergue</p>
	<p>Prix Libre</p>
	<p class="mt-8">Les infos arrivent !</p>
</main>
