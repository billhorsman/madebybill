<template>
  <section class="container">
    <article class="gallery">
      <h1>Lonely Whale</h1>
      <p>by Bill Horsman, 2019</p>
      <figure>
        <figcaption>
          Original ink on paper drawing
        </figcaption>
        <img src="/images/lonely-whale-orig.png" alt="Original Ink on Paper">
      </figure>
      <figure>
        <figcaption>
          Coloured and cropped with Photoshop
        </figcaption>
        <img src="/images/lonely-whale-colour.png" alt="With Colour">
      </figure>
      <figure>
        <figcaption>
          Greyscale intensity of
          <span class="blue-swatch">blue</span>
          (for <a href="https://en.wikipedia.org/wiki/Risograph">Risograph</a>)
        </figcaption>
        <img src="/images/lonely-whale-blue.png" alt="Blue">
      </figure>
      <figure>
        <figcaption>
          Greyscale intensity of
          <span class="black-swatch">black</span>
          (for <a href="https://en.wikipedia.org/wiki/Risograph">Risograph</a>)
        </figcaption>
        <img src="/images/lonely-whale-black.png" alt="Black">
      </figure>
    </article>
  </section>
</template>

<script>

export default {
  head: {
    title: 'Lonely Whale by Bill Horsman'
  },
  meta: [
    { hid: 'description', name: 'description', content: 'Ink then Photoshop' },
    { property: 'og:title', content: 'Lonely Whale by Bill' },
    { property: 'og:description', content: 'Ink then Photoshop' },
    { property: 'og:url', content: 'https://www.madebybill.co.uk/discover/lonely-whale' },
  ]
}
</script>

<style lang="scss">
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
  display: inline-block;
  margin-right: 0.5rem;
  padding: 0 0.2rem;
}
.black-swatch {
  background: #0C0A07;
  color: white;
  @extend .swatch;
}
.blue-swatch {
  background: #3B425E;
  color: white;
  @extend .swatch;
}
</style>
