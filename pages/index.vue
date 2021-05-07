<template>
  <div class="">
    <!-- <zoom></zoom> -->
    <div class="theheader">
      <img
        src="https://www.ababank.com/typo3conf/ext/boxmodel/Resources/Private/Templates/ABA/images/aba-web-top-logo.png"
        width="30"
        height="30"
      />
      <div>Sina testing</div>
    </div>
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <pinch-zoom>
      <zoom></zoom>
    </pinch-zoom>
    <div class="thefooter">
      <button>Pay now</button>
    </div>
  </div>
</template>

<script>
import zoom from '@/components/zoom'
export default {
  components: {
    zoom,
  },
}
</script>

<style>
.thefooter {
  position: fixed;
  bottom: 0;
  width: 100%;
  border-top: 1px solid #ccc;
  background: #fff;
  height: 105px;
  padding-top: 15px;
  transform: scale(8);
  -webkit-transform: scale3d(8);
  text-align: center;
}
.thefooter button {
  transform: scale(1);
  -webkit-transform: scale3d(1);
}
.theheader {
  position: fixed;
  top: 155px;
  z-index: 11;
  width: 100%;
  background: #fff;
  padding: 10px;
  border-bottom: 1px solid #ccc;

  transform: scale(5);
  -webkit-transform: scale3d(5);
  text-align: center;
}
.theheader div,
.theheader img {
  transform: scale(1);
  -webkit-transform: scale3d(1);
}
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
