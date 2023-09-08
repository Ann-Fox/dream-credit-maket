<script setup>
import IconRightArrow from './icons/IconRightArrow.vue';
import IconContactUs from './icons/IconContactUs.vue'
</script>

<template>
  <section class="contact">

    <div class="contact__content center">
      <div class="breadcrumbs">
        <ul class="breadcrumbs__ul">
          <li>Best credit offers<IconRightArrow></IconRightArrow></li>
          <li>Contact Us<IconRightArrow></IconRightArrow></li>
        </ul>
      </div>

      <div class="contact__us">
        <h1>CONTACT US</h1>
        <img :src={IconContactUs} alt="">
      <div class="contact__us__text">
        <p>We welcome your comments, questions, or any request you may have! If you would like to contact our staff, please complete the form below.</p>
        <p>We will respond to your inquiries ASAP!</p>
      </div>
      </div>
    </div>

  </section>

</template>

<style scoped>
.contact {
  background: url('/home/annfox/dream-credit-maket/public/contact-us-bg.jpg');
  padding: 16px 0 65px;
}

.breadcrumbs__ul {
  display: flex;
}
.breadcrumbs__ul li {
  display: flex;
  text-align: center;
}
</style>
