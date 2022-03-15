<template>
  <footer>{{ data.footer }}</footer>
</template>

<script>
import data from "@/data/config.yml";

export default {
  data() {
    return {
      data,
    };
  },
};
</script>
