<script setup lang="ts">
import {ref} from 'vue';
import Child from './Child.vue';

const name = ref('initial');
</script>

<template>
	<h1>{{name}}</h1>
	<Child @changeName="n => name = n" />
</template>