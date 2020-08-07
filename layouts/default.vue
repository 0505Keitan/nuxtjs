<template>
  <div>
    <Nuxt />
  </div>
</template>

<style>
html {
  font-family:
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

.btn {
  display: inline-block;
  border-radius: 4px;
  text-decoration: none;
  padding: 10px 25px;
  margin: 5px;
  transition: 0.5s;
}

.button--green {
  border: 1px solid #3b8070;
  color: #3b8070;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  border: 1px solid #35495e;
  color: #35495e;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}

.button--blue {
  border: 1px solid #1DA1F2;
  color: #1DA1F2;
}

.button--blue:hover {
  color: #fff;
  background-color: #1DA1F2;
}

.button--red {
  border: 1px solid #FF0000;
  color: #FF0000;
}

.button--red:hover {
  color: #fff;
  background-color: #FF0000;
}
</style>
