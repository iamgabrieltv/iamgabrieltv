<script>
	import '../app.css';
	import { browser } from '$app/environment';

	function getRandomInt(max) {
		return Math.floor(Math.random() * max);
	}

	var aURL = 'https://www.youtube.com/watch?v=KmtzQCSh6xk';

	if (browser) {
		if (getRandomInt(2) == 0) {
			console.log('Match!');
		} else {
			console.log('No Match!');
			aURL = 'https://www.youtube.com/watch?v=ZZ5LpwO-An4';
		}
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
	<a href={aURL} id="DONT">
		<p>!!DO NOT CLICK!!</p>
	</a>
</div>
