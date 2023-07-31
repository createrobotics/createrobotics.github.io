<script lang="ts">
	import cogwheel from "./assets/cogwheel.gif";
	import discordLogo from "./assets/discord-mark-white.svg";
	import githubLogo from "./assets/github-mark-white.svg";
	import roboticsLogo from "./assets/icon.png";
	import youtubeLogo from "./assets/yt_icon_mono_dark.png";
</script>

<main>
	<div class="homeContainer">
		<div class="logoContainer">
			<img src={cogwheel} class="largeCogwheel" alt="Spinning cogwheel" />
			<img src={roboticsLogo} class="roboticsLogo" alt="Robotics logo" />
		</div>
		<h1>Create Robotics</h1>
		<p>A computer mod with programming for Create</p>
		<div class="buttonContainer">
			<a class="buttonLink" target="_blank" href="">
				<button class="selectionButton"> docs </button>
			</a>
			<a
				class="buttonLink"
				target="_blank"
				href="https://discord.com/invite/jvVbwBYMU9"
			>
				<button class="selectionButton">
					<img
						src={discordLogo}
						class="buttonLogo"
						alt="Discord logo"
					/>
				</button>
			</a>
			<a
				class="buttonLink"
				target="_blank"
				href="https://github.com/Worker20/CreateRobotics"
			>
				<button class="selectionButton">
					<img
						src={githubLogo}
						class="buttonLogo"
						alt="Discord logo"
					/>
				</button>
			</a>
			<a
				class="buttonLink"
				target="_blank"
				href="https://youtube.com/@CreateRoboticsMod"
			>
				<button class="selectionButton">
					<img
						src={youtubeLogo}
						class="buttonLogo"
						alt="Youtube logo"
					/>
				</button>
			</a>
		</div>
	</div>
</main>
