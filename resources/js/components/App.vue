<template>
    <p>{{ msg }}</p>
</template>
<script setup lang="ts">
import { ref } from "vue";

const msg = ref<string>("Hello world");
</script>
<style lang="scss"></style>
