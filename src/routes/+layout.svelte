<script>
	import Meta from './Meta.svelte';
</script>

<nav>
	<ul>
		<li><a href="/">home</a></li>
		<li><a href="/woo">woo</a></li>
		<li><a href="/blah">blah</a></li>
	</ul>
</nav>

<p>
	When you client-side navigate between pages you will get a second <code>&lt;title&gt;</code> tag appended
</p>

<svelte:head>
	<Meta />
</svelte:head>

<slot />
