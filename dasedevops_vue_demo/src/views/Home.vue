<template>
  <div class="home">
    <login/>
  </div>
</template>

<script>
// @ is an alias to /src
import login from "@/components/login.vue";

export default {
  name: "Home",
  components: {
    login
  },
};
</script>
