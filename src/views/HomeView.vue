<template>
  <div class="home">
    <number-roll ref="numberRoll" :startNumber='1' :endNumber="123" roll-height="120px" />
  </div>
</template>

<script>
// @ is an alias to /src
import numberRoll from 'vue2-number-roll'

export default {
  name: "HomeView",
  components: {
    numberRoll
  }
};
</script>
