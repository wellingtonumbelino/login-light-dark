<template>
	<div class="login">
		<div class="login-container">
			<div class="welcome-message">
				<h1>Welcome Back!</h1>
			</div>
			<div class="login-actions">
				<h1>Login</h1>
			</div>
		</div>
	</div>
</template>

<script setup lang="ts">
import { ref } from 'vue';

const message = ref("Hello World");
</script>

<style lang="scss">
@import './login-style.scss'
</style>