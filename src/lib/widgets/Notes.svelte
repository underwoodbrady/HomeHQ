<script lang="ts">
	import Widget from '$lib/Widget.svelte';
</script>

<Widget>
	<section slot="header" class="mb-5 flex justify-between items-center">
		<h2 class="text-lg font-semibold">My Note</h2>
		<p class="text-sm font-light">Menu</p>
	</section>
	<div slot="body" class="ml-1 space-y-2">
		<p class="text-sm">
			Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque aliquam, dui varius
			iaculis blandit, orci ligula sollicitudin sapien, dapibus posuere nulla velit eget ligula. In
			laoreet velit augue, vitae fermentum augue bibendum a.
		</p>
	</div>
	<section slot="footer">
		<p class="text-xs font-light">Last Updated 8:16PM</p>
	</section>
</Widget>
