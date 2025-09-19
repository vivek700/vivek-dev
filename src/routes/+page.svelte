<script lang="ts">
	import gitlab from '$lib/icons/gitlab.svg';
	import github from '$lib/icons/github_dark.svg';
	import bluesky from '$lib/icons/bluesky.svg';
</script>

<svelte:head>
	<title>vivek</title>
	<meta
		name="description"
		content="Personal page for Vivek, featuring links to his Github, Gitlab and social profiles."
	/>
</svelte:head>

<div class="flex h-dvh flex-col items-center justify-center text-white">
	<h1 class="text-4xl font-bold">Vivek</h1>
	<div class="flex items-center gap-x-4 pt-1">
		<a title="bluesky" href="https://bsky.app/profile/vivek.sbs" target="_blank">
			<img src={bluesky} alt="bluesky icon" width="25" height="25" />
		</a>
		<a title="gitlab" href="https://gitlab.com/vivek.me" target="_blank">
			<img src={gitlab} alt="gitlab icon" width="25" height="25" />
		</a>
		<a title="github" href="https://github.com/vivek700" target="_blank">
			<img src={github} alt="github icon" width="25" height="25" />
		</a>
	</div>
</div>
