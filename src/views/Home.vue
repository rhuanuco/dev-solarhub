<template>
  <div class="container mt-10">
    <div class="flex flex-cols-2">
      <Menu class="w-1/5" />
      <Header />
    </div>
  </div>
  
</template>

<script>
// @ is an alias to /src
import Header from "../components/Header.vue";
import Menu from "../components/Menu.vue";

export default {
  name: "Home",
  components: { Header,Menu }
};
</script>
