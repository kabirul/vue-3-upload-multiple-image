<template>
  <div id="app">
    <div class="container" style="width:600px">
      <div style="margin:50px 0;">
        <p id="devname"><span>Amica</span></p>
        <h4 style="margin-top:20px">Vue.js 3 upload multiple Images</h4>
      </div>
      <upload-images></upload-images>
    </div>
	<footer-page></footer-page>
  </div>
</template>
<script>
import UploadImages from "./components/UploadImages";
import FooterPage from './components/Footer';

export default {
  name: "App",
  components: {
    UploadImages,
	FooterPage
  }
};
</script>
<style>
#devname span{ background-color:#000000; color:#FFFFFF; width:100px; height:100px; padding:20px 10px; border-radius:50%; font-size:15px; }
</style>