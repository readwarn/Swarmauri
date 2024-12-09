<template>
  <div>
    DEMO OF SWARMKIT-UI BY {{ name }}
    <Button type="primary"> Submit </Button>
  </div>
</template>

<script lang="ts" setup>
import { ref } from "vue";
import { Button } from "@swarmakit/vue";
const name = ref("Rilwan");
</script>
