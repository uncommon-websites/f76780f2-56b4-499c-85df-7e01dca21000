<script lang="ts">
	import { page } from "$app/state";
</script>

<main class="page">
	<h1>Error {page.status}</h1>
	<p>{page.error?.message ?? "Da ist etwas schiefgelaufen."}</p>
	<a href="/">Zurück zur Startseite</a>
</main>
