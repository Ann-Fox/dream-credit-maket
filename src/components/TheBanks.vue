<script setup>
const banks = [
  {
    name: 'BOFI',
    phone: '800-955-7070',
    img: '/img/bank1.png'
  },
  {
    name: 'CAPITAL ONE®',
    phone: '800-955-7070',
    img: '/img/bank2.png'
  },
  {
    name: 'CAPITAL BANK',
    phone: '800-955-7070',
    img: '/img/bank3.png'
  },
  {
    name: 'CREDIT ONE BANK®',
    phone: '800-955-7070',
    img: '/img/bank4.png'
  },
  {
    name: 'METABANK',
    phone: '800-955-7070',
    img: '/img/bank5.png'
  },
  {
    name: 'MID AMERICA BANK',
    phone: '800-955-7070',
    img: '/img/bank6.png'
  },
  {
    name: 'SIMMONS FIRST',
    phone: '800-955-7070',
    img: '/img/bank7.png'
  },
  {
    name: 'USAA',
    phone: '800-955-7070',
    img: '/img/bank8.png'
  },
]

</script>

<template>
  <div>
<h1>CONTACT INFORMATION OF BANKS:</h1>
<div v-for="bank in banks" :key="bank.name">
  <img :src="bank.img" alt="">
  <img src="/img/bank-line.svg" alt="line">
  <div>
    <h3>{{ bank.name }}:</h3>
    <p>
      Customer Service:<br>
      {{ bank.phone }}
    </p>
    
  </div>
</div>
  </div>
</template>

<style scoped>

</style>
