<template>
  <div class="spa-footer">
    <div class="row m-auto mt-2">
      <div class="col-2">
        <a class="socialLogos" target="_blank" href="https://facebook.com">
          <img
            id="facebookLogo"
            src="/img/social/facebook.png"
            alt="Logo Facebook"
        /></a>
      </div>
      <div class="col-2">
        <a class="socialLogos" target="_blank" href="https://twitter.com">
          <img id="xLogo" src="/img/social/twitter.png" alt="Logo X"
        /></a>
      </div>
      <div class="col-2">
        <a
          class="socialLogos"
          target="_blank"
          href="https://github.com/APedrosaUab"
        >
          <img id="githubLogo" src="/img/social/github.png" alt="Logo Github"
        /></a>
      </div>
      <div class="col-2">
        <a class="socialLogos" target="_blank" href="https://www.discogs.com">
          <img
            id="discogsLogo"
            src="/img/social/discogs.png"
            alt="Logo DiscoGS"
        /></a>
      </div>
      <div class="col-2">
        <a class="socialLogos" target="_blank" href="https://www.youtube.com">
          <img
            id="youtubeLogo"
            src="/img/social/youtube.png"
            alt="Logo Youtube"
        /></a>
      </div>
      <div class="col-2">
        <a
          class="socialLogos"
          target="_blank"
          href="https://www.linkedin.com/in/pedrosandre/"
        >
          <img
            id="linkedinLogo"
            src="/img/social/linkedin.png"
            alt="Logo Linkedin"
        /></a>
      </div>
      <div class="col-12">
        <p>André Pedrosa, 2023 © Todos os Direitos Reservados.</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FooterSection",
};
</script>

<style scoped>

.spa-footer {
  min-height: 60px;
  align-content: center;
  display: grid;
}

.spa-footer p {
  margin-top: 10px;
  margin-bottom: 10px;
  font-size: 12px;
}

.socialLogos img {
  width: 50px;
  max-width: 100%;
  height: auto;
}
</style>
