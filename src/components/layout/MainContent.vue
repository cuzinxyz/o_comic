<template>
  <div
    class="w-full lg:w-4/5 p-4 h-screen overflow-y-auto scroll-smooth [&::-webkit-scrollbar]:w-1 [&::-webkit-scrollbar-track]:bg-gray-100 [&::-webkit-scrollbar-thumb]:bg-gray-300 dark:[&::-webkit-scrollbar-track]:bg-neutral-700 dark:[&::-webkit-scrollbar-thumb]:bg-neutral-500"
  >
    <slot></slot>
  </div>
</template>

<script setup lang="ts"></script>
