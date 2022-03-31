<script>
// import { defineComponent } from '@vue/composition-api'

export default {
  name: 'Section1',

}
</script>

<template>
  <section class="section-1" id="section-1">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-md-6 col-style">
          <img src="../../assets/section-1pic.PNG" alt="who we are">
        </div>
        <div class="col-md-6 col-style">
          <h5>About</h5>
          <h3>Who we <span>are</span></h3>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. 
            Repudiandae numquam totam laborum nostrum, debitis quae vero sequi reprehenderit quaerat, 
            odit non voluptates dignissimos reiciendis, alias quos ipsum? Minus, unde quo.</p>
          <button>More Details</button>
        </div>
      </div>
    </div>
  </section>  
</template>

<style scoped>
  .section-1 {
    padding: 150px 0 200px 0;
  }

  .section-1 .col-style {
    margin: auto;
    padding: 0 35px 0 35px;
  }

  .section-1 .col-style h5 {
    font-weight: 650;
  }
  
  .section-1 .col-style h3 {
    font-weight: 900;
    font-size: 3rem;
  }

  .section-1 .col-style h3 span {
    color: rgb(255, 217, 0);
  }

  .section-1 .col-style p {
    font-weight: 600;
  }

  .section-1 .col-style img {
    width: 100%;
    /* height: 35vmin; */
    object-fit: contain;
    /* border-radius: 0.6em 0.6em 0 0; */
  }
  .section-1 .col-style button {
    border: none;
    background: rgb(255, 217, 0);
    color: #000;
    margin: 40px 0 0 0;
    padding: 10px 30px 10px 30px;
    border-radius: 10px;
    font-size: 1.2em;
    font-weight: 600;
  }

  @media (min-width: 1600px) {
    .section-1 {
      padding: 0px 0 150px 0;
    }
  }
</style>