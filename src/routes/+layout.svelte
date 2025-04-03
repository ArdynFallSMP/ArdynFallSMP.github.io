<script lang="ts">
	import '../app.css';
	import '@fortawesome/fontawesome-free/css/all.min.css'
	let { children } = $props();
</script>

{@render children()}
{@html '<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" />'}