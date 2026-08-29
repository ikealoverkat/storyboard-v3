<script lang="ts">
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
	<!-- how does storyboard work? -->
	<div
		class="flex flex-col items-center justify-center gap-4 bg-purple-darkest bg-[url('/bg-window.png')] bg-cover p-12 text-center"
	>
		<h1 class="text-glow text-4xl text-whiteish">HOW DOES STORYBOARD WORK?</h1>
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
				<img class="mx-auto mt-4 h-[200px] w-full outline" />
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
				<img class="mx-auto mt-4 h-[200px] w-full outline" />
			</div>
			<div class="how-container">
				<div class="flex flex-row items-center justify-start gap-6">
					<div class="how-number bg-blue">4</div>
					<h1 class="text-3xl text-purple-darkest">code</h1>
				</div>
				<p class="mt-2 leading-5 text-purple-darkest">
					First ever coding project? We reccomend using <a href="https://www.renpy.org/" target="_blank" class="underline hover:decoration-wavy text-purple-mid">Ren'Py</a>. Check out our <a href="placeholder" class="underline hover:decoration-wavy text-purple-mid">guides!</a>
					You can use whatever you want, though!
				</p>
				<img class="mx-auto mt-4 h-[200px] w-full outline" />
			</div>
			<div class="how-container">
				<div class="flex flex-row items-center justify-start gap-6">
					<div class="how-number bg-pink-purple">5</div>
					<h1 class="text-3xl text-purple-darkest">publish to itch.io</h1>
				</div>
				<p class="mt-2 leading-5 text-purple-darkest">
					lorem ipsum dolor sit amet. i forgot the rest of it but it's okay..
				</p>
				<img class="mx-auto mt-4 h-[200px] w-full outline" />
			</div>
			<div class="how-container">
				<div class="flex flex-row items-center justify-start gap-6">
					<div class="how-number bg-[#b2b1f0]">6</div>
					<h1 class="text-3xl text-purple-darkest">submit for prize!!!</h1>
				</div>
				<p class="mt-2 leading-5 text-purple-darkest">
					lorem ipsum dolor sit amet. i forgot the rest of it but it's okay..
				</p>
				<img class="mx-auto mt-4 h-[200px] w-full outline" />
			</div>
		</div>
		<h2 class="text-2xl m-4 text-white prizes-text">...and we'll send you prizes!</h2>
		<!-- scrolling prizes add them later tho -->
		<div class="prize-scroll">
			<div class="prize-track">
				<div class="prize-set">
					<div class="prize-card bg-magenta text-whiteish">prize 1</div>
					<div class="prize-card bg-blue text-whiteish">prize 2</div>
					<div class="prize-card bg-teal text-purple-darkest">prize 3</div>
					<div class="prize-card bg-pink-purple text-purple-darkest">prize 4</div>
					<div class="prize-card bg-yellow text-purple-darkest">prize 5</div>
					<div class="prize-card bg-purple-mid text-whiteish">prize 6</div>
				</div>
				<div class="prize-set" aria-hidden="true">
					<div class="prize-card bg-magenta text-whiteish">prize 1</div>
					<div class="prize-card bg-blue text-whiteish">prize 2</div>
					<div class="prize-card bg-teal text-purple-darkest">prize 3</div>
					<div class="prize-card bg-pink-purple text-purple-darkest">prize 4</div>
					<div class="prize-card bg-yellow text-purple-darkest">prize 5</div>
					<div class="prize-card bg-purple-mid text-whiteish">prize 6</div>
				</div>
			</div>
		</div>
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
</div>
