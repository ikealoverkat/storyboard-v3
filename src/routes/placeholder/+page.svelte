<script lang="ts">
	function goBack(e: any) {
		e.preventDefault();
		history.back();
	}
</script>

<div
	class="placeholder flex h-screen w-screen flex-col items-center justify-center bg-[url('/bg-window.png')] bg-cover text-center"
>
	<div class="z-10 flex flex-col items-center justify-center gap-4">
		<button
			onclick={goBack}
			class="text-glow text-xl text-teal underline hover:decoration-wavy"><i>← back</i></button
		>
		<h1 class="text-glow text-4xl text-whiteish">looks like this page doesn't exist yet.</h1>
		<p class="text-glow text-2xl text-yellow">
			it will soon though!! once storyboard fully launches, you shouldn't be able to find this page.
			<br />if you do, PLSPLSPLS dm
			<a href="https://hackclub.enterprise.slack.com/team/U08H34LLQQJ">@kat</a>
			on slack or email
			<a href="mailto:kat@hackclub.com">kat@hackclub.com</a> and tell her how you got here.
			<br /> uh oh....
		</p>
	</div>
</div>

<style>
	.placeholder::before {
		position: absolute;
		backdrop-filter: blur(4px);
		content: '';
		width: 100vw;
		height: 100vh;
		background-color: color-mix(in srgb, black 60%, transparent);
	}
</style>
