<template>
  <h1>
    <Hello />
  </h1>
</template>

<script>
import Hello from "~/components/Hello";

export default {
  components: {
    Hello
  },
  data() {
    return {
      msg: "hello vue"
    };
  },
  methods: {    

  }
};
</script>
