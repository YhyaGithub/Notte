<script lang="ts">
	import '../../styles/note.scss';
</script>

<svelte:head>
	<title>Notte | New Note</title>
</svelte:head>

<div>
	<h1>New Note</h1>
	<input type="text" id="title" placeholder="Title" />
	<textarea id="note" cols="35" rows="30" placeholder="Note" />
</div>
