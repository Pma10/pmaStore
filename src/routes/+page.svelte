<script>

</script>

<svelte:head>
	<title>메인</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<ul class="items-list">
	<li>
		<div>
			<h3>PMA</h3>
			<p>프마를 소개합니다</p>
		</div>
	</li>
	<li>
		<div>
			<h3>나</h3>
			<p>나를 소개합니다</p>
		</div>
	</li>
	<li>
		<div>
			<h3>너</h3>
			<p>너를 소개합니다</p>
		</div>
	</li>
</ul>

<style>
	.items-list{
		color: #e6e7eb;
		list-style: none;
		display: flex;
		align-items: center;
		justify-content: center;
	}
	.items-list li div{
		background-color: #303034;
		margin-right: 3em;
		width: 15em;
		border-radius: 1em;
		text-align: center;
		padding: 12em 0;
		transition: background-color 0.2s linear;
	}
	.items-list li div:hover{
		background-color: #42424d;
	}
	::selection{
		background: rgb(168, 166, 166);
	}
</style>
