<template>
  <section class="video-container">
    <video autoplay muted loop id="myVideo">
      <source
        src="../../../assets/videos/video-background-desktop.mp4"
        type="video/mp4"
      />
    </video>
  </section>
  <div class="container-fluid aboutUs">
    <div class="content">
      <div class="row">
        <div
          class="col-12 mb-5 d-flex align-items-center justify-content-center"
        >
          <div class="logoWrapper">
            <img
              src="../../../assets/img/minutentagLogo.png"
              alt="minutentagLogo"
            />
          </div>
        </div>
      </div>
      <div class="row my-5">
        <h1
          class="mainTitle text-center d-flex align-items-center justify-content-center"
        >
          Taking your ideas <br />
          to the next level
        </h1>
      </div>
      <div class="row my-5">
        <div class="col-12 d-flex align-items-center justify-content-center">
          <div class="buttonWrapper">
            <button-component
              :linkTo="'https://www.minutentag.com/contact-us'"
              text="Let's work together!"
            />
          </div>
        </div>
      </div>
      <div class="row my-5">
        <h1
          class="title text-center d-flex align-items-center justify-content-center"
        >
          Custom software solutioning to <br />
          support high demanding businesses
        </h1>
      </div>
    </div>
  </div>
</template>

<script>
import ButtonComponent from "../../ui-components/ButtonComponent/ButtonComponent.vue";

export default {
  components: { ButtonComponent },
};
</script>

<style scoped>
.logoWrapper {
  margin-top: 4rem;
}

#myVideo {
  position: absolute;
  top: 0;
  left: 50%;
  width: 100%;
  height: max-content;
  -ms-transform: translateX(-50%);
  -moz-transform: translateX(-50%);
  -webkit-transform: translateX(-50%);
  transform: translateX(-50%);
  z-index: -100;
  background-size: cover;
}

.content {
  position: relative;
}
</style>
