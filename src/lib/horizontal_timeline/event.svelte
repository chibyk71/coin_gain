<script lang="ts">
	import { onMount } from "svelte";
	import { writable } from "svelte/store";
	import {  dates, newDateIndex, oldDateIndex, parseDate } from "./timeline.svelte";
	
    export let date: number|string = "";
	let id:number,classEntering:string,classLeaving:string,animationEnded = writable(false);
	$:{if ($newDateIndex > $oldDateIndex) {
		classEntering = 'selected enter-right'
		classLeaving = 'leave-left';
	} else if($newDateIndex < $oldDateIndex) {
		classEntering = 'selected enter-left'
		classLeaving = 'leave-right';
	} else {
		classEntering = 'selected'
		classLeaving = '';
	}}
	
    onMount(() =>{
		date = new Date(parseDate(date as string)).getTime();
        $dates.push(date)
		id = $dates.indexOf(date);
    })
</script>
<li class="{id == $newDateIndex ? classEntering: classLeaving}" on:animationstart={() =>  $animationEnded = false} on:animationend={() => $animationEnded = true }  class:leave-right={!$animationEnded && (id == $oldDateIndex)} class:leave-left={!$animationEnded && (id == $oldDateIndex)}>
	<slot />
</li>