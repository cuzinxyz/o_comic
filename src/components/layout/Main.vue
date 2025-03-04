<script setup lang="ts">
import Sidebar from './partials/Sidebar.vue';
</script>

<template>
    <div class="bg-gray-900 text-white">
        <div class="flex flex-col lg:flex-row min-h-screen">
            <Sidebar />

            <slot></slot>
        </div>
    </div>
</template>