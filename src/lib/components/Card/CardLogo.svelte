<script lang="ts">
	export let src: string;
	export let alt: string;
	export let size = 50;
	export let radius = '15px';
	export let classes = '';
</script>

<img
	class={`card-logo ${classes} aspect-square`}
	{src}
	{alt}
	height={size}
	width={size}
	style={`border-radius:${radius};`}
/>
