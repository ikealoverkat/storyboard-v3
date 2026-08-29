<script lang="ts">
	interface Prize {
		title: string;
		hours: string;
		description: string;
		src: string;
	}
	const prizes: Prize[] = [
		{
			title: 'Steam Dev License',
			hours: '30 hours',
			description: 'upload your game to steam!!! get big money?',
			src: '/prizes/steamlicense.jpg'
		},
		{
			title: 'Hoodie? 👀👀👀👀👀',
			hours: '15 hours',
			description: 'sparkly shiny and theres a funny cat too',
			src: '/prizes/hoodie.png'
		},
		{
			title: 'Drawing Tablet',
			hours: '50 hours',
			description: 'draw a visual novel & get a drawing tablet to... draw more visual novels',
			src: '/prizes/drawingtablet.webp'
		},
		{
			title: 'Fat Cat Plushie',
			hours: '15 hours',
			description: 'SOO CUTE',
			src: '/prizes/plushie.jpg'
		},
		{
			title: 'Stickers',
			hours: '1 hour',
			description: 'cool stickers drawn by the supercoolawesome storyboard team!',
			src: '/prizes/stickersheet.png'
		},
		{
			title: 'Keyboard',
			hours: '20 hours',
			description: 'click click clack clack',
			src: '/prizes/steamlicense.jpg'
		}
	];

	const prizeColors = [
		{ bg: 'var(--color-magenta)', text: 'var(--color-whiteish)' },
		{ bg: 'var(--color-blue)', text: 'var(--color-whiteish)' },
		{ bg: 'var(--color-teal)', text: 'var(--color-purple-darkest)' },
		{ bg: 'var(--color-pink-purple)', text: 'var(--color-purple-darkest)' },
		{ bg: 'var(--color-yellow)', text: 'var(--color-purple-darkest)' },
		{ bg: 'var(--color-purple-mid)', text: 'var(--color-whiteish)' }
	];
</script>

<div>
	<!-- hero -->
	<div
		class="hero flex h-screen w-screen flex-col items-center justify-center gap-2 bg-[url('/bg-hero.png')] bg-cover"
	>
		<img
			src="/logo-with-caption.png"
			alt="hack club's storyboard: for teens 13-18"
			class="m-4 w-1/3"
		/>
		<h1 class="text-glow text-3xl text-teal">make a visual novel, get cool prizes!</h1>
		<div class="m-6 flex w-1/2 flex-row items-center justify-center gap-4">
			<input
				type="text"
				class="w-2/3 rounded-4xl bg-whiteish p-3 px-5 text-xl text-purple-mid outline-2 outline-purple-dark drop-shadow-sm drop-shadow-purple-darkest"
				placeholder="your@email.com"
			/>
			<button
				class="ok-btn rounded-4xl p-4 text-2xl outline outline-purple-darkest drop-shadow-sm drop-shadow-purple-darkest hover:drop-shadow-md hover:drop-shadow-purple-darkest"
				>OK!</button
			>
		</div>
	</div>
	<!-- windows -->
	<div
		class="flex flex-col items-center justify-center gap-4 bg-purple-darkest bg-[url('/bg-window.png')] bg-cover text-center"
	>
		<!-- how it work? -->
		<div class="flex flex-col items-center justify-center gap-4">
			<h1 class=" text-glow mt-16 text-4xl text-whiteish">HOW DOES STORYBOARD WORK?</h1>
			<h2 class="text-glow m-4 text-2xl text-teal">learn how to make a visual novel...</h2>
			<div class="grid w-2/3 grid-cols-3 grid-rows-2">
				<div class="how-container">
					<div class="flex flex-row items-center justify-start gap-6">
						<div class="how-number bg-magenta">1</div>
						<h1 class="text-3xl text-purple-darkest">sign up!</h1>
					</div>
					<p class="mt-2 leading-5 text-purple-darkest">
						lorem ipsum dolor sit amet. i forgot the rest of it but it's okay..
					</p>
					<img class="mx-auto mt-4 h-[200px] w-full outline" alt="" />
				</div>
				<div class="how-container">
					<div class="flex flex-row items-center justify-start gap-6">
						<div class="how-number bg-teal">2</div>
						<h1 class="text-3xl text-purple-darkest">write a story</h1>
					</div>
					<p class="mt-2 leading-5 text-purple-darkest">
						lorem ipsum dolor sit amet. i forgot the rest of it but it's okay..
					</p>
					<img class="mx-auto mt-4 h-[200px] w-full outline" />
				</div>
				<div class="how-container">
					<div class="flex flex-row items-center justify-start gap-6">
						<div class="how-number bg-yellow">3</div>
						<h1 class="text-3xl text-purple-darkest">draw</h1>
					</div>
					<p class="mt-2 leading-5 text-purple-darkest">
						lorem ipsum dolor sit amet. i forgot the rest of it but it's okay..
					</p>
					<img class="mx-auto mt-4 h-[200px] w-full outline" alt="" />
				</div>
				<div class="how-container">
					<div class="flex flex-row items-center justify-start gap-6">
						<div class="how-number bg-blue">4</div>
						<h1 class="text-3xl text-purple-darkest">code</h1>
					</div>
					<p class="mt-2 leading-5 text-purple-darkest">
						First ever coding project? We reccomend using <a
							href="https://www.renpy.org/"
							target="_blank"
							class="text-purple-mid underline hover:decoration-wavy">Ren'Py</a
						>. Check out our
						<a href="placeholder" class="text-purple-mid underline hover:decoration-wavy">guides!</a
						>
						You can use whatever you want, though!
					</p>
					<img class="mx-auto mt-4 h-[200px] w-full outline" alt="" />
				</div>
				<div class="how-container">
					<div class="flex flex-row items-center justify-start gap-6">
						<div class="how-number bg-pink-purple">5</div>
						<h1 class="text-3xl text-purple-darkest">publish to itch.io</h1>
					</div>
					<p class="mt-2 leading-5 text-purple-darkest">
						lorem ipsum dolor sit amet. i forgot the rest of it but it's okay..
					</p>
					<img class="mx-auto mt-4 h-[200px] w-full outline" alt="" />
				</div>
				<div class="how-container">
					<div class="flex flex-row items-center justify-start gap-6">
						<div class="how-number bg-[#b2b1f0]">6</div>
						<h1 class="text-3xl text-purple-darkest">submit for prize!!!</h1>
					</div>
					<p class="mt-2 leading-5 text-purple-darkest">
						lorem ipsum dolor sit amet. i forgot the rest of it but it's okay..
					</p>
					<img class="mx-auto mt-4 h-[200px] w-full outline" alt="" />
				</div>
			</div>
		</div>

		<h2 class="prizes-text m-4 text-2xl text-white">...and we'll send you prizes!</h2>
		<!-- scrolling prizes  -->
		<div class="prize-scroll">
			<div class="prize-track">
				<div class="prize-set">
					{#each prizes as prize, i}
						<div
							class="prize-card flex flex-col items-center justify-between p-4 text-center"
							style="background-color: {prizeColors[i % prizeColors.length]
								.bg}; color: {prizeColors[i % prizeColors.length].text}"
						>
							<h1 class="mt-4 text-3xl underline">{prize.title}</h1>
							<p class="mt-4 text-lg">{prize.description}</p>
							<img
								src={prize.src}
								alt={prize.title}
								class="m-4 w-full flex-1 rounded-sm object-contain"
							/>
							<p class="text-lg">{prize.hours}</p>
						</div>
					{/each}
				</div>
				{#each prizes as prize, i}
					<div
						class="prize-card flex flex-col items-center justify-between p-4 text-center"
						style="background-color: {prizeColors[i % prizeColors.length].bg}; color: {prizeColors[
							i % prizeColors.length
						].text}"
					>
						<h1 class="mt-4 text-3xl underline">{prize.title}</h1>
						<p class="mt-4 text-lg">{prize.description}</p>
						<img
							src={prize.src}
							alt={prize.title}
							class="m-4 w-full flex-1 rounded-sm object-contain"
						/>
						<p class="text-lg">{prize.hours}</p>
					</div>
				{/each}
			</div>
		</div>
		<!-- guides -->
		<div class="guides w-full flex flex-col items-center justify-center gap-4 text-center">
			<h2>we have step-by-step guides to help:</h2>
			<div class="grid w-5/12 grid-cols-2">
				<div class="guide-container">
					<p>hi</p>
					<p>hi</p>
				</div>
				<div class="guide-container">2</div>
				<div class="guide-container">3</div>
				<div class="guide-container">4</div>
				<div class="guide-container">5</div>
				<div class="guide-container">6</div>
			</div>
			<a href="placeholder">view more →</a>
			<h2>and a collection of <a href="placeholder">free resources</a> for you to use! :)</h2>
		</div>
	</div>
</div>
<!-- examples & faq -->
<div class="flex flex-col items-center justify-center gap-2 text-center">
	<!-- examples -->
	<div>
		<h1>example projects</h1>
		<p>Look at these cool projects other Storyboarders have made & get inspired!</p>
		<br />Stuck on ideas? explore the <a href="placeholder">#storyboard</a> channel & feel free to
		ask questions.
		<!-- TV w projects - make a componentn later or sum -->
		<div></div>
	</div>
	<!-- faq -->
	<div>
		<h1>FAQ</h1>
		<!-- (embed w renpy game) -->
		<h2>
			More questions? ask in <a href="placeholder">#storyboard-help</a> or email
			<a href="mailto:kat@hackclub.com">kat@hackclub.com</a>
		</h2>
	</div>
</div>
<!-- footer -->
<div class="flex flex-col items-center justify-center gap-2 text-center">
	<h1>made with ♡ by teens, for teens</h1>
	<!-- team -->
	<div></div>
	<p>
		<a href="https://hackclub.com">hack club</a> ✦ <a href="https://slack.hackclub.com">slack</a>
		✦ <a href="https://clubs.hackclub.com">clubs</a> ✦
		<a href="https://conduct.hackclub.com">code of conduct</a>
	</p>
	<p>this website is <a href="https://github.com/ikealoverkat/storyboard-v3">open source!</a></p>
</div>
