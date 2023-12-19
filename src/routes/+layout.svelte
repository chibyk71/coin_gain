<script lang="ts">
	import { onMount } from "svelte";
    import "../style.postcss"
	import { fade } from "svelte/transition";
    let preloader = true;
    onMount(() => {
        preloader = !preloader
    })
</script>
<svelte:head>
    <link rel="stylesheet" href="../../vendor/animation/sal.css">
</svelte:head>
{#if preloader}
    <div id="preloader" transition:fade={{duration:500}}><i>.</i><i>.</i><i>.</i></div>
{/if}

{#if !preloader}
    <slot></slot>
{/if}