<template>
  <h5>{{ data.title }}</h5>
</template>

<script>
import data from "@/data/config.yml";

export default {
  methods: {
    routeIdentify: function (route, name) {
      route = route.split("/");
      if (route[1] == name.toLowerCase()) {
        return "active";
      } else {
        return "";
      }
    },
  },
  data() {
    return {
      data,
    };
  },
};
</script>
