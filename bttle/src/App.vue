<script setup lang="ts">
import { Button } from '@/components/ui/button';
</script>

<template>
  <h1 class="text-red-500 font-extrabold">You did it!</h1>
  <p>
    Visit <a href="https://vuejs.org/" target="_blank" rel="noopener">vuejs.org</a> to read the
    documentation
  </p>
  <div class="min-h-screen min-w-screen flex items-center justify-center">
    <Button variant="outline">
      Click me
    </Button>
  </div>
</template>

<style scoped>
</style>
