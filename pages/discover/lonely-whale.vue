<template>
  <section class="container">
    <Gallery>
      <header>
        <nav>
          <h1>Lonely Whale</h1>
          <p>by Bill Horsman, 2019</p>
          <a class="discover" href="/discover">
            <i class="fas fa-long-arrow-alt-left"></i>
            <span>Other Art</span>
          </a>
        </nav>
        <img src="/images/lonely-whale.gif" alt="Cruel Sea">
      </header>
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
          Greyscale
          <span class="blue-swatch">blue</span>
        </figcaption>
        <img src="/images/lonely-whale-blue.png" alt="Blue">
      </figure>
      <figure>
        <figcaption>
          Greyscale
          <span class="black-swatch">black</span>
        </figcaption>
        <img src="/images/lonely-whale-black.png" alt="Black">
      </figure>
      <RisoImage src="/images/lonely-whale-printed.png"></RisoImage>
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
