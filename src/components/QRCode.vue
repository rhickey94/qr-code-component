<script setup></script>
<template>
  <section class="qr-card">
    <div class="image-container">
      <img src="../assets/image-qr-code.png" alt="weenus" />
    </div>
    <h2>Improve your front-end skills by building projects</h2>
    <p>
      Scan the QR code to visit Frontend Mentor and take your coding skills to
      the next level
    </p>
  </section>
</template>
<style lang="scss" scoped>
.qr-card {
  padding: 16px;
  max-width: 320px;
  background-color: var(--vt-c-white);
  border-radius: 20px;

  h2 {
    font: var(--vt-f-header);
    color: var(--vt-c-dark-navy);
    text-align: center;
    margin-bottom: 16px;
  }
  p {
    font: var(--vt-f-body);
    color: var(--vt-c-gray);
    text-align: center;
    margin: 0 auto 24px;
    width: 256px;
  }
}

.image-container {
  margin: 0 auto;
  margin-bottom: 24px;
  img {
    border-radius: 10px;
    width: auto;
    height: auto;
    max-width: 288px;
    max-height: 288px;
  }
}
</style>
