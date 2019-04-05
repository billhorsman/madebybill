<template lang="html">
  <article class="gallery">
    <slot></slot>
  </article>
</template>

<script>
export default {
}
</script>

<style lang="scss" scoped>
article {
  margin: 3rem;
}
h1, p {
  text-align: left;
}
figure {
  margin: auto;
  width: 70%;
}
figcaption {
  margin: 3rem 0 1rem;
}
img {
  border: 1px solid #eee;
  box-shadow: 0 0 20px rgba(0, 0, 0, 0.2);
  width: 100%;
}
.swatch {
  color: white;
  display: inline-block;
  margin: 0 0.25rem;
  padding: 0 0.3rem;
  text-transform: uppercase;
  transform: rotate(-10deg);
}
.grey-swatch {
  @extend .swatch;
  background: #454545;
}
.teal-swatch {
  @extend .swatch;
  background: #0F7963;
}
.green-swatch {
  @extend .swatch;
  background: #20903E;
}
.purple-swatch {
  @extend .swatch;
  background: #683385;
}
.yellow-swatch {
  @extend .swatch;
  background: #F4D522;
}
.bright-red-swatch {
  @extend .swatch;
  background: #C11E21;
}
.medium-blue-swatch {
  @extend .swatch;
  background: #19589F;
}
.blue-swatch {
  @extend .swatch;
  background: #238BCA;
}
.orange-swatch {
  @extend .swatch;
  background: #E2664A;
}
.fluoro-pink-swatch {
  @extend .swatch;
  background: #DA4E8D;
}
.black-swatch {
  @extend .swatch;
  background: #0C0A07;
}
</style>
