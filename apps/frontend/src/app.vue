<template>
  <NuxtLayout>
    <ModrinthLoadingIndicator />
    <Notifications />
    <NuxtPage />
  </NuxtLayout>
</template>
<script setup lang="ts">
// bleh.
import ModrinthLoadingIndicator from "~/components/ui/modrinth-loading-indicator.ts";
import Notifications from "~/components/ui/Notifications.vue";
</script>
