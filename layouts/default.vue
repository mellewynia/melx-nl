<template>
  <div>
    <nuxt />
  </div>
</template>

<style>
html {
  min-height: 100vh;
  background: #40d0f7; /* // #50daff; */
  background-image: linear-gradient(40deg, rgba(1, 129, 172, 0.2), rgba(0, 0, 0, 0));
  /**
  linear-gradient(40deg, rgba(0, 0, 0, 0.16), rgba(0, 0, 0, 0))
  linear-gradient(40deg, rgba(37, 255, 84, 0.16), rgba(0, 0, 0, 0))
  */
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  background: #2572ff;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}
</style>
