<script>
    import { page } from '$app/stores';
    import Back from "$lib/Back.svelte";

    const {children} = $props();
</script>

<svelte:options runes={true} />

{$page.url.pathname}


<a href="./">+layout href = ./</a>

<Back />

{@render children()}
