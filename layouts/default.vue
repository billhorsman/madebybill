<template>
  <div>
    <nuxt/>
  </div>
</template>

<style lang="scss">
@import url('https://fonts.googleapis.com/css?family=Overlock:400,700|Ubuntu+Mono');
html {
  background: white;
  color: black;
  font-family: "Overlock", Arial, sans-serif;
  font-size: 18px;
  box-sizing: border-box;
}

*, *:before, *:after {
  box-sizing: border-box;
  margin: 0;
}
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
a {
  color: blue;
  &:visited {
    color: blue;
  }
  &:hover {
    color: red;
  }
}
</style>
