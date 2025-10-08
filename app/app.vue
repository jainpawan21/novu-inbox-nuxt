<script setup lang="ts">
import NovuInbox from "./components/NovuInbox.vue";
</script>

<template>
  <div>
    <NuxtRouteAnnouncer />
    <!-- <NuxtWelcome /> -->
    <ClientOnly>
      <NovuInbox />
    </ClientOnly>
  </div>
</template>
