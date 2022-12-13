<template>
  <div class="contact-info-container">
    <h1 class="name">Chris Yu</h1>
    <div class="contact-info">
      <span>+86 13438128255</span>
      <span class="divider"></span>
      <span>yuetong3yu@gmail.com</span>
      <span class="divider"></span>
      <span>Auckland, NZ</span>
    </div>
    <div class="brief-intro">
      A Front End Developer used to work at Fortune 500 with 4 years of
      experience.
    </div>
  </div>
</template>

<style scoped>
.contact-info-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 1mm;
}
.name {
  font-size: 1.5em;
  font-weight: bold;
  text-align: center;
}
.contact-info {
  display: flex;
  align-items: center;
}
.divider {
  display: inline-block;
  width: 0.5mm;
  height: 6mm;
  margin: 0 2mm;
  background-color: black;
}
</style>
