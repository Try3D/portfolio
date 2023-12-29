<script lang="ts">
	import '../app.scss';
</script>

<header>
	<nav>
		<div class="left-items">
			<a href="/"><div>Home</div></a>
			<a href="/projects"><div>Projects</div></a>
			<a href="/blogs"><div>Blogs</div></a>
			<a href="/about"><div>About</div></a>
		</div>
		<div class="right-items">
			<a href="mailto:rsarans186@gmail.com"><div>Mail</div></a>
			<a href="https://github.com/try3d/"><div>Github</div></a>
			<a href="https://linkedin.com/in/saran-shankar/"><div>Linkedin</div></a>
		</div>
	</nav>
</header>

<slot />

<div class="center">Copyright 2023 try3d. All rights reserved.</div>

<style lang="scss">
	a {
		color: $blue;
		text-decoration: none;
	}

	nav {
		display: flex;
	}

	.left-items,
	.right-items {
		display: flex;
		a {
			div {
				display: flex;
			}
		}
	}

	.right-items {
		margin-left: auto;
	}
</style>
