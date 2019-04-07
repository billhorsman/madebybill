<template>
  <section class="container">
    <article>
      <h1>Art by Bill Horsman</h1>
      <p>This is an experiment.</p>
      <figure>
        <figcaption>
          <a href="/discover/cruel-sea">Cruel Sea</a>
        </figcaption>
        <a href="/discover/cruel-sea">
          <img src="/images/cruel-sea-printed.png" alt="Cruel Sea">
        </a>
      </figure>
      <figure>
        <figcaption>
          <a href="/discover/lonely-whale">Lonely Whale</a>
        </figcaption>
        <a href="/discover/lonely-whale">
          <img src="/images/lonely-whale-printed.png" alt="Lonely Whale">
        </a>
      </figure>
    </article>
  </section>
</template>

<script>

export default {
  head: {
    title: 'Discover Art by Bill Horsman'
  },
  meta: [
    { hid: 'description', name: 'description', content: 'This is an experiment' },
    { property: 'og:title', content: 'Discover Art by Bill Horsman' },
    { property: 'og:description', content: 'This is an experiment' },
    { property: 'og:url', content: 'https://www.madebybill.co.uk/discover' },
  ]
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
}
figcaption {
  margin: 3rem 0 1rem;
}
img {
  border: 1px solid #ddd;
  box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
  max-width: 600px;
  width: 100%;
}
</style>
