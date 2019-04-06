<template>
  <section class="container">
    <Gallery>
      <h1>Cruel Sea</h1>
      <p>by Bill Horsman, 2019</p>
      <p>
        <a class="discover" href="/discover">
          <i class="fas fa-long-arrow-alt-left"></i>
          <span>Other Art</span>
        </a>
      </p>
      <figure>
        <figcaption>
          Original ink on paper drawing
        </figcaption>
        <img src="/images/cruel-sea-orig.png" alt="Original Ink on Paper">
      </figure>
      <figure>
        <figcaption>
          Coloured and cropped with Photoshop
        </figcaption>
        <img src="/images/cruel-sea-colour.png" alt="With Colour">
      </figure>
      <figure>
        <figcaption>
          Greyscale intensity of
          <span class="blue-swatch">blue</span>
        </figcaption>
        <img src="/images/cruel-sea-blue.png" alt="Blue">
      </figure>
      <figure>
        <figcaption>
          Greyscale intensity of
          <span class="black-swatch">black</span>
        </figcaption>
        <img src="/images/cruel-sea-black.png" alt="Black">
      </figure>
      <RisoImage src="/images/cruel-sea-printed.png"></RisoImage>
    </Gallery>
  </section>
</template>

<script>
import Gallery from "../../components/Gallery";
import RisoImage from "../../components/RisoImage";

export default {
  components: {
    Gallery,
    RisoImage
  },
  head: {
    title: 'Cruel Sea by Bill Horsman'
  },
  meta: [
    { hid: 'description', name: 'description', content: 'Ink then Photoshop' },
    { property: 'og:title', content: 'Cruel Sea by Bill Horsman' },
    { property: 'og:description', content: 'Ink then Photoshop' },
    { property: 'og:url', content: 'https://www.madebybill.co.uk/discover/cruel-sea' },
  ]
}
</script>
