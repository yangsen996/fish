<template>
	<view class="container">
		{{msg}}
	</view>
</template>

<script setup>
import { ref } from "vue";
	const msg = ref("test")
</script>

<style>
	.container {
		padding: 20px;
		font-size: 14px;
		line-height: 24px;
	}
</style>
