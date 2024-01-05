<script lang="ts">
  import GithubIcon from '$lib/icons/github.svelte'
  import LinkedinIcon from '$lib/icons/linkedin.svelte'
</script>

<svelte:head>
	<title>Sayan</title>
</svelte:head>

<div class="home-container">
	<h1>Sayan Dutta</h1>
	<div>
		<p>Software Engineer</p>
    <p><a href="resume.pdf">Résumé</a></p>
		<p>
			<a class="icon" href="https://github.com/supersayan">
				<GithubIcon />
			</a>
			<a class="icon" href="https://linkedin.com/in/s4y4n">
				<LinkedinIcon />
			</a>
		</p>
	</div>
</div>

<style>
	.home-container {
		flex: 1;
		display: flex;
		flex-direction: column;
		align-items: flex-start;
		justify-content: center;
		margin: 2rem;
		min-height: 400px;
	}

	@media (max-width: 800px) {
		.home-container {
			flex-direction: column;
		}
	}
</style>
