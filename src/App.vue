<template>
  <h1>
    {{ message }}
  </h1>
  <TestImageComponent/>
</template>

<script setup lang="ts">
import {TestImageComponent} from '@ce335805/test-image-component'

const message: String = "This consumes my image component"
</script>
