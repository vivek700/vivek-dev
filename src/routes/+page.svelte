<script lang="ts">
	import gitlab from '$lib/icons/gitlab.svg';
	import github from '$lib/icons/github_dark.svg';
</script>

<svelte:head>
	<title>vivek</title>
	<meta
		name="description"
		content="Personal page for Vivek, featuring links to his Github and Gitlab profiles."
	/>
</svelte:head>

<div class="flex h-lvh flex-col items-center justify-center text-white">
	<h1 class="text-2xl">Vivek</h1>
	<div class="flex gap-x-4 pt-1">
		<a title="github" href="https://github.com/vivek700" target="_blank">
			<img src={github} alt="github icon" width="20" height="20" />
		</a>
		<a title="gitlab" href="https://gitlab.com/vivek.me" target="_blank">
			<img src={gitlab} alt="gitlab icon" width="20" height="20" />
		</a>
	</div>
</div>
