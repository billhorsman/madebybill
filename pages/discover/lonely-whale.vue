<template>
  <section class="container">
    <Gallery>
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
    </Gallery>
  </section>
</template>

<script>
import Gallery from "../../components/Gallery";

export default {
  components: {
    Gallery
  },
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
