<template>
  <h1>{{ data.title }}</h1>
</template>

<script>
import data from "@/data/home/hero.yml";

export default {
  data() {
    return {
      data,
    };
  },
};
</script>
