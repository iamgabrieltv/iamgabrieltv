<script>
	import '../app.css';
	import { browser } from '$app/environment';

	function RandomRedirect() {
		var random = Math.floor(Math.random() * 10);

		switch (random) {
			case 0:
				window.open('https://www.youtube.com/watch?v=ZZ5LpwO-An4');
				break;
			case 1:
				window.open('https://www.youtube.com/watch?v=KmtzQCSh6xk');
				break;
			case 2:
				window.open('https://www.youtube.com/watch?v=fC7oUOUEEi4');
				break;
			case 3:
				window.open('https://www.youtube.com/watch?v=CzwVoc1MsGo');
				break;
			case 4:
				window.open('https://www.youtube.com/watch?v=D-UmfqFjpl0');
				break;
			case 5:
				window.open('https://www.youtube.com/watch?v=b8HO6hba9ZE');
				break;
			case 6:
				window.open('https://www.youtube.com/watch?v=d1YBv2mWll0');
				break;
			case 7:
				window.open('https://www.youtube.com/watch?v=7zpxgyG7eGk');
				break;
			case 8:
				window.open('https://www.youtube.com/watch?v=tMV2oE0BjUo');
				break;
			case 9:
				window.open('https://www.youtube.com/watch?v=FCai_OTxpv4');
				break;
		}
	}

	if (browser) {
		console.log('Client-Side connection established');
	}
</script>

<h1>Hello Hooman!</h1>

<p>
	I see you stumbled upon my page! I am Gabriel and I do coding and stuff. My current project is
	this:
</p>

<div style="width:500px;height:500px;border:0px; background-color:white;">
	<iframe
		style="width: 500px; height: 500px;border: 0;"
		src="https://b.0-0.plus/blog/md.htm?src=https://raw.githubusercontent.com/iamgabrieltv/MC-Streamoverlay-Server/main/README.md"
	/>
</div>

<p>I have some more projects! Check them out on my GitHub!</p>
<a href="https://github.com/iamgabrieltv?tab=repositories">
	<img
		alt="GitHub Repos"
		src="https://img.shields.io/static/v1?label=GitHub Repos&message=2&logo=github&style=for-the-badge&color=191919&labelColor=black&logoColor=white"
	/>
</a>

<p>
	I also contribute to the German Minecraft Server <a href="https://github.com/EarthBuild"
		>Earthbuild</a
	>.
</p>

<div class="footer">
	<p>Made with ❤ in Germany 🇩🇪</p>
	<a on:click={RandomRedirect} id="DONT" class="clickable">
		<p>!!DO NOT CLICK!!</p>
	</a>
</div>
