<script setup>
import { RouterLink, useRouter } from 'vue-router'
const router = useRouter()
const goBack = () => router.back()
</script>
<template>
  <section>
    <div class="container m-auto py-6 px-6">
      <button
        @click="goBack"
        class="text-green-500 hover:text-green-600 flex items-center cursor-pointer"
      >
        <i class="pi pi-arrow-circle-left mr-3"></i> Back
      </button>
    </div>
  </section>
</template>
