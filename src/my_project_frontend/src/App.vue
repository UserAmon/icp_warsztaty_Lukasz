<template>
  <div class="bg-gray-400">
<Header/>
<Calculator />
</div>
</template>

<script>

import Header from  "./components/Header.vue";
import Calculator from  "./components/Calculator.vue";

export default {
  name: "App",
  components: {
    Header,
    Calculator,
  },
};
</script>