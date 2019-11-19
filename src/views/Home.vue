<template>
  <div class="home">
    <!-- msg内容传入helloworld组件 -->
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <!-- <h2>{{ mes }}</h2> -->
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "home",
  components: {
    HelloWorld
  },
  data() {
    return {
      mes: "this is home page"
    };
  }
};
</script>
