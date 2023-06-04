<script setup lang="ts">
const emit = defineEmits<{
	changeName: [name: string];
}>();
</script>

<template>
	<button @click="() => emit('changeName', 'foo')">
		Change name
	</button>
</template>