<script>
</script>

<header class="header">
	<div class="header-inner inner">
		<h1 class="header-title"><a href="/">資産管理</a></h1>
		<nav class="header-nav">
			<ul class="header-nav-list">
				<li class="header-nav-item"><a class="header-nav-item-link" href="/dashboard">資産</a></li>
				<li class="header-nav-item"><a class="header-nav-item-link" href="#">レポート</a></li>
				<li class="header-nav-item"><a class="header-nav-item-link" href="#">記録</a></li>
				<li class="header-nav-item"><a class="header-nav-item-link" href="#">設定</a></li>
			</ul>
		</nav>
	</div>
</header>

<style>
	* {
		box-sizing: border-box;
	}

	.header {
		background: lightblue;
		position: fixed;
		top: 0;
		left: 0;
		right: 0;
    height: 80px;
	}

	.inner {
		/* max-width: 1000px; */
		margin: 0 auto;
		padding: 0 40px;
	}

	.header-inner {
		display: flex;
		align-items: center;
    height: 100%;
	}

	.header-title a {
		color: #333;
		font-size: 24px;
		font-weight: bold;
	}

	.header-nav {
		margin-left: auto;
	}

	.header-nav-list {
		display: flex;
	}

	.header-nav-item:not(:first-child) {
		margin-left: 40px;
	}

	.header-nav-item-link {
		display: block;
		color: #333;
		height: 80px;
		line-height: 80px;
	}

	ul {
		list-style: none;
	}

	a {
		text-decoration: none;
	}
</style>
