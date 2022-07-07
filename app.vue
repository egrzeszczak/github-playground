<script setup>
const route = useRoute()
</script>


<template>
	<div style="text-align: center">
		<img
			src="/img/picture.png"
			alt="Discover Github"
			style="width: 120px"
		/>
		<pre>{{route}}</pre>
	</div>
</template>
