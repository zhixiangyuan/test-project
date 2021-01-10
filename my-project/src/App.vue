<template>
  <div id="app">
    <img class="cover-body" src="./assets/background-img-02.jpg">
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
* {
  margin: 0px;
  border: 0px;
  padding: 0px;
}

html, body {
  background-size:100%;
}

img.cover-body {
  top: 0;
  left: 0;
  max-width: 100%;
  height: 100vh;
  display: flex;
  flex-wrap: nowrap;
  flex-direction: column;
  align-items: center;
  align-self: center;
  align-content: center;
  position: relative;
  overflow: hidden;
  margin-bottom: -100px;
      position: absolute;
    width: 100%;
    height: 100%;
    background-position: center;
    background-size: cover;

  box-sizing: border-box;
  display: block;
  position: absolute;

  animation-delay: 0s;
  animation-duration: .5s;
  animation-fill-mode: forwards;
  animation-timing-function: ease-out;
  animation-name: fadeInAnimation;
}

@keyframes fadeInAnimation {
  0% {
    opacity: 0;
    filter: blur(12px);
    transform: scale(1.02);
  }

  100% {
    opacity: 1;
    filter: blur(0.5px);
  }
}

</style>
