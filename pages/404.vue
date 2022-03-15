<template>
  <h1>{{ data.title }}</h1>
</template>
<script>
import data from "@/data/config.yml";

export default {
  data() {
    return {
      data,
    };
  },
  layout: "emptyLayout",
  head() {
    return {
      title: "JackCreative 404",
    };
  },
};
</script>
