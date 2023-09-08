<script setup>
import IconMailAdress from './icons/IconMailAdress.vue';


</script>

<template>
  <section class="address">
    <div class="address__group">
      <IconMailAdress></IconMailAdress>
      <div>
        <h2>
        MAILING ADDRESS:
      </h2>
      <address>
        1680 South Ashland Ave Suit# 3007<br>
        Chicago, IL 60608-2013
      </address>
    </div>
    </div>
  </section>
</template>

<style scoped>
.address {
  background: #CFEFFF;
  padding: 28px 0;
}

.address__group {
  display: flex;
    align-items: center;
    justify-content: center;
    gap: 30px;
}

h2 {
  margin-bottom: 13px;
}
</style>
