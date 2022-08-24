<script>
	import { page } from '$app/stores';

	let title;
	let description;

	$: {
		$page;
		title = Math.random();
		description = Math.random();
	}
</script>

<title>{title}</title>
<meta name="description" content={description} />
