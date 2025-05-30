<script lang="ts">

	let { onClick, text } = $props();

</script>

bbb<button
	class="button"
	on:click={onClick}
>
	{#if text}
		<span class="label">{text}</span>
	{/if}
</button>button
