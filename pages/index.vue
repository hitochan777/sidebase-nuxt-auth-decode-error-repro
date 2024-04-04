<script setup lang="ts">
import { definePageMeta } from '#imports'

definePageMeta({ auth: false })
</script>

<template>
  <div>
    <nuxt-link to="/">
      -> manual login, logout, refresh button
    </nuxt-link>
    <br>
    <div>select one of the above actions to get started.</div>
  </div>
</template>
