<template lang="html">
  <figure>
    <figcaption>
      Printed using the
      <a href="https://en.wikipedia.org/wiki/Risograph">Risograph</a>
      at the
      <a href="https://www.dca.org.uk/visit/print-studio">DCA Print Studio</a>
    </figcaption>
    <img :src="src" alt="Black">
  </figure>
</template>

<script>
export default {
  props: ["src"]
}
</script>

<style lang="scss" scoped>
figure {
  margin: auto;
  width: 70%;
}
figcaption {
  margin: 3rem 0 1rem;
}
img {
  border: 1px solid #ddd;
  box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
  width: 100%;
}
</style>
