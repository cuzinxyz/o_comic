<script setup lang="ts">
import { ref } from 'vue';
import Editor from 'primevue/editor';

const value = ref('');

</script>

<template>
  <Editor v-model="value" editorStyle="min-height: 100vh" />
</template>
