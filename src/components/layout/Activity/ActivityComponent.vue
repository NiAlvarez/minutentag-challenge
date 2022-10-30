<template>
  <div class="container my-5">
    <div class="card customCard my-5">
      <div
        class="card-body d-flex justify-content-center align-items-center flex-column flex-md-row"
      >
        <div class="col-6 d-flex justify-content-center align-items-center">
          <img src="../../../assets/img/team.png" alt="teamImage" />
        </div>
        <div
          class="col-6 col-xs-12 d-flex flex-column justify-content-center align-items-center"
        >
          <p class="cardTitle text-sm-center">Team & Staff Augmentation</p>
          <p class="cardContent mx-5 text-sm-center">
            We empower your work team & provide knowledgeable and scalable
            consultants.
          </p>
          <button-component
            :buttonType="'btn btn-secondary'"
            text="Learn more"
            class="my-2"
            :linkTo="'https://www.minutentag.com/our-services'"
          />
        </div>
      </div>
    </div>
    <div class="container">
      <div class="card customCard my-5">
        <div
          class="card-body d-flex justify-content-center align-items-center flex-column-reverse flex-md-row"
        >
          <div
            class="col-6 d-flex flex-column justify-content-center align-items-center"
          >
            <p class="cardTitle text-sm-center">Product Development & UX</p>
            <p class="cardContent mx-5 text-sm-center">
              We cover all stages of consulting, design, development, testing
              and full journey life-cycle management for your idea.
            </p>
            <button-component
              :buttonType="'btn btn-secondary'"
              text="Learn more"
              class="my-2"
              :linkTo="'https://www.minutentag.com/our-services'"
            />
          </div>
          <div class="col-6 d-flex justify-content-center">
            <img src="../../../assets/img/product.png" alt="productImage" />
          </div>
        </div>
      </div>
    </div>
    <div class="container">
      <div class="card customCard my-5">
        <div
          class="card-body d-flex justify-content-center align-items-center flex-column flex-md-row"
        >
          <div class="col-6 d-flex justify-content-center">
            <img src="../../../assets/img/goverment.png" alt="govermentImage" />
          </div>
          <div
            class="col-6 d-flex flex-column justify-content-center align-items-center"
          >
            <p class="cardTitle text-sm-center">Government Solutions</p>
            <p class="cardContent text-sm-center mx-5">
              Intelligence, Analytics and technology solutions to help
              governments become safer, efficient and more productive.
            </p>
            <button-component
              :buttonType="'btn btn-secondary'"
              text="Learn more"
              class="my-2"
              :linkTo="'https://www.minutentag.com/our-services'"
            />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import ButtonComponent from "../../ui-components/ButtonComponent/ButtonComponent.vue";

export default {
  components: {
    ButtonComponent,
  },
};
</script>

<style scoped>
body {
  background-color: #efedec;
}
.customCard {
  border-radius: 20px;
  border-color: #ffff;
}
</style>
