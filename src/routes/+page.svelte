<script lang="ts">
	import Widget from '$lib/Widget.svelte';
	import Time from '$lib/widgets/Time.svelte';
	import Notes from '$lib/widgets/Notes.svelte';
	import RaspPi from '$lib/widgets/RaspPi.svelte';
	import Todos from '$lib/widgets/Todos.svelte';
	import Weather from '$lib/widgets/Weather.svelte';
	import TallWidget from '$lib/TallWidget.svelte';
	import Financials from '$lib/widgets/Financials.svelte';

    //Most recently focused widget gets brighter colors
</script>

<div class="space-y-6">
	<div class="flex flex-1 flex-wrap justify-around">
		<Widget />
        <TallWidget/>
		<Time />
		<Weather />
	</div>
	<div class="flex flex-1 flex-wrap justify-around">
		<RaspPi />
		<Todos />
		<Notes />
        <Financials/>
	</div>
</div>

<div class="wrapper mb-5">
    <div class="one grid-item rounded-sm drop-shadow-md">One</div>
    <div class="two grid-item rounded-sm drop-shadow-md">Two</div>
    <div class="three grid-item rounded-sm drop-shadow-md">Three</div>
    <div class="four grid-item rounded-sm drop-shadow-md">Four</div>
    <div class="five grid-item rounded-sm drop-shadow-md">Five</div>
    <div class="six grid-item rounded-sm drop-shadow-md">Six</div>
    <div class="seven grid-item rounded-sm drop-shadow-md">Seven</div>
    <div class="eight grid-item rounded-sm drop-shadow-md">Eight</div>
    <div class="nine grid-item rounded-sm drop-shadow-md">Nine</div>
</div>

<div class="wrapper">
    <div class="one"><Time /></div>
    <div class="two"><TallWidget/></div>
    <div class="three"><Todos /></div>
    <div class="four"><RaspPi /></div>
    <div class="five"><Weather /></div>
    <div class="six"><Notes /></div>
    <div class="seven">  <Financials/></div>
    <div class="eight"><Widget /></div>
    <div class="nine">Nine</div>
</div>

<style>
.wrapper {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 20px;
  grid-auto-rows: 280px;
}

.grid-item{
    background-color:rgba(26, 235, 131, 0.2);
    border:2px solid white;

}
.one {
  grid-column: 1;
  grid-row: 1;
}
.two {
  grid-column: 2;
  grid-row: 1 / 3;
}
.three {
  grid-column: 3;
  grid-row: 1;
}
.four {
  grid-column: 4;
  grid-row: 1;
}
.five {
  grid-column: 1;
  grid-row: 2;
}
.six {
  grid-column: 3;
  grid-row: 2;
}
.seven {
  grid-column: 4;
  grid-row: 2/4;
}
.eight {
  grid-column: 1;
  grid-row: 3;
}
.nine {
  grid-column: 2/4;
  grid-row: 3;
}
</style>
