<template>
  <div class="container">
    <div class="row">
      <h1
        class="title text-center d-flex align-items-center mt-5 justify-content-center"
      >
        People are the key to success
      </h1>
    </div>
    <div class="row my-5">
      <div class="col-md-6 col-xs-12">
        <div class="d-flex justify-content-center">
          <img
            src="../../../assets/img/integrity.png"
            class="my-4"
            alt="integrityIcon"
          />
        </div>
        <div
          class="d-flex flex-column justify-content-center align-items-center"
        >
          <p class="cardTitle">Integrity</p>
          <p class="cardSubtitle">'Always do the right thing'</p>
          <p class="cardContent text-center">
            Customer relationship is our greatest asset. <br />
            We know that working ethically, responsibly and respectfully
          </p>
          <button-component
            :buttonType="'btn btn-secondary'"
            class="my-2"
            text="Learn more"
            :linkTo="'https://www.minutentag.com/about-us'"
          />
        </div>
      </div>
      <div class="col-md-6 col-xs-12">
        <div class="d-flex justify-content-center">
          <img
            src="../../../assets/img/ownership.png"
            class="my-4"
            alt="ownershipIcon"
          />
        </div>
        <div
          class="d-flex flex-column justify-content-center align-items-center"
        >
          <p class="cardTitle">Ownership</p>
          <p class="cardContent text-center">
            We are accountable during every step of the <br />
            process. We devote our complete <br />
            dedication and knowledge to arrive at <br />
            consistent efficient end to end solutions.
          </p>
          <button-component
            :buttonType="'btn btn-secondary'"
            class="my-2"
            text="Learn more"
            :linkTo="'https://www.minutentag.com/about-us'"
          />
        </div>
      </div>
    </div>
    <div class="row my-5">
      <div class="col-md-6 col-xs-12">
        <div class="d-flex justify-content-center">
          <img
            src="../../../assets/img/flexibility.png"
            alt="flexibilityIcon"
            class="my-4"
          />
        </div>
        <div
          class="d-flex flex-column justify-content-center align-items-center"
        >
          <p class="cardTitle">Flexibility</p>
          <p class="cardContent text-center">
            We provide customized solutions. Each <br />
            project has its own features. Adapting to <br />
            schedules, objectives and people is the key <br />
            to achieving success.
          </p>
          <button-component
            :buttonType="'btn btn-secondary'"
            class="my-2"
            text="Learn more"
            :linkTo="'https://www.minutentag.com/about-us'"
          />
        </div>
      </div>
      <div class="col-md-6 col-xs-12">
        <div class="d-flex justify-content-center">
          <img
            src="../../../assets/img/innovation.png"
            class="my-4"
            alt="innovationIcon"
          />
        </div>
        <div
          class="d-flex flex-column justify-content-center align-items-center"
        >
          <p class="cardTitle">Innovation</p>
          <p class="cardContent text-center">
            We have a constant- learning culture. <br />
            Using the best & latest technology. We <br />
            stimulate creative and sustainable <br />
            solutioning.
          </p>
          <button-component
            :buttonType="'btn btn-secondary'"
            class="my-2"
            text="Learn more"
            :linkTo="'https://www.minutentag.com/about-us'"
          />
        </div>
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
body {
  background-color: #efedec;
}
</style>
