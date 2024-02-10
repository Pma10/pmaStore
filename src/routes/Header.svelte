<script>
	import logo from '$lib/images/logo.png';
</script>

<header>
	<div class="nav-logo">
		<a href="/">
			<img src={logo} alt="logo" />
		</a>
	</div>

	<nav>
		<ul>
			<li>
				<a href="/">메인</a>
			</li>
			<li>
				<a href="/about">찾아보기</a>
			</li>
			<li>
				<a href="/help">도움</a>
			</li>
		</ul>
	</nav>
</header>

<style>
	@import url("https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/variable/pretendardvariable.min.css");
	
	header {
		font-family: 'Pretendard Variable';
		font-weight: 700;
		color: aliceblue;
		display: flex;
		justify-content: space-between;
	}

	::selection{
		background: rgb(168, 166, 166);
	}

	.nav-logo {
		width: 3em;
		height: 3em;
	}

	.nav-logo a {
		display: flex;
		align-items: center;
		justify-content: center;
		width: 100%;
		height: 100%;
	}

	.nav-logo img{
		width: 5em;
		height: 6.5em;
		object-fit: contain;
	}

	nav {
		display: flex;
		justify-content: center;
	}

	ul {
		position: relative;
		padding: 0;
		margin: 0;
		height: 3em;
		display: flex;
		justify-content: center;
		align-items: center;
		list-style: none;
	}

	li {
		position: relative;
		height: 100%;
	}

	nav a {
		display: flex;
		height: 100%;
		align-items: center;
		margin-right: 1em;
		padding: 0 1em;
		text-decoration: none;
		transition: color 0.2s linear;
		transition: background-color 0.2s linear;
		color: rgba(231, 231, 224, 0.945);
	}

	a:hover {
		color: #FFFFFF;
	    background-color: #42424d;
		border-radius: 5px;
	}
</style>
