<template>
  <section class="container">
    <div>
      <h1 class="title">
        Made by Bill
      </h1>
      <h2 class="subtitle">
        Print <span>&amp;</span> Ink
      </h2>
      <ul>
        <li>
          <a href="mailto:hi@madebybill.co.uk" class="mail">
            <i class="far fa-fw fa-envelope"/>
            hello@madebybill.co.uk
          </a>
        </li>
      </ul>
    </div>
  </section>
</template>

<script>

export default {
  components: {
  }
}
</script>

<style lang="scss">

h1 {
  font-size: 3rem;
  font-weight: bold;
  padding: 0 1rem;
}
h2 {
  font-size: 3rem;
  font-weight: lighter;
  padding: 0 1rem;
  text-transform: uppercase;
  span {
    color: #777;
    font-weight: normal;
    vertical-align: top;
  }
}
@media (max-width: 550px) {
  h1 {
    font-size: 1.8rem;
  }
  h2 {
    font-size: 1.8rem;
  }
}

ul {
  display: inline-block;
  font-family: "Ubuntu Mono";
  letter-spacing: 1px;
  margin: 2rem 0 0;
  padding: 0;
  > li {
    list-style: none;
    margin: 0;
    padding: 0;
    text-align: left;
  }
  a {
    border-radius: .5rem;
    color: #aaa;
    display: inline-block;
    padding: 1rem;
    text-decoration: none;
    transition: all .3s;
    i {
      margin-right: .5rem;
    }
    &:hover {
      background: #222;
      color: white;
    }
    &.twitter {
      i {
        color: #4C9FEC;
      }
    }
    &.instagram {
      i {
        color: #ED4A55;
      }
    }
    &.facebook {
      i {
        color: #4A66AD;
      }
    }
  }
}
</style>
