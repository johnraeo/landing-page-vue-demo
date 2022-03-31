<script>
// import { defineComponent } from '@vue/composition-api'

export default {
  name: 'Section3',

}
</script>

<template>
  <section class="section-3">
    <h2>Our <span>Pricing</span> Plan</h2>
    <div class="container">
      <div class="row">
        <div class="col-md-4">
          <div class="col-style">
            <h4>Starter Plan</h4>
            <h3>$24.99</h3>
            <h4>Per Month</h4>
            <ul>
              <li>1 - 3 website pages</li>
              <li>Responsive Design</li>
              <li>Social Media Integration</li>
              <li>Contact Form</li>
              <li>Google Maps</li>
              <li>Photo Sourcing</li>
              <li>2 Rounds of Revisions</li>
              <li>Website Design Mock Up</li>
            </ul>
            <a>https://my-templates.online/numerio/home.html</a>
          </div>
        </div>
        <div class="col-md-4">
          <div class="col-style col-style-diff">
            <h4>Starter Plan</h4>
            <h3>$27.99</h3>
            <h4>Per Month</h4>
            <ul>
              <li>1 - 3 website pages</li>
              <li>Responsive Design</li>
              <li>Social Media Integration</li>
              <li>Contact Form</li>
              <li>Google Maps</li>
              <li>Photo Sourcing</li>
              <li>2 Rounds of Revisions</li>
              <li>Website Design Mock Up</li>
            </ul>
            <a>https://my-templates.online/numerio/home.html</a>
          </div>
        </div>
        <div class="col-md-4">
          <div class="col-style">
            <h4>Starter Plan</h4>
            <h3>$33.99</h3>
            <h4>Per Month</h4>
            <ul>
              <li>1 - 3 website pages</li>
              <li>Responsive Design</li>
              <li>Social Media Integration</li>
              <li>Contact Form</li>
              <li>Google Maps</li>
              <li>Photo Sourcing</li>
              <li>2 Rounds of Revisions</li>
              <li>Website Design Mock Up</li>
            </ul>
            <a>https://my-templates.online/numerio/home.html</a>
          </div>
        </div>
      </div>
    </div>
    <button>See All Prices</button>
  </section>  
</template>

<style scoped>
  .section-3 {
    background: #fff;
    padding: 20px 0 100px 0;
    text-align: center;
  }

  .section-3 h2 {
    /* text-align: center; */
    font-weight: 700;
    font-size: 2.5rem;
    margin: 0 0 30px 0;
  }

  .section-3 h2 span {
    color: rgb(255, 217, 0);
  }

  .section-3 .col-style {
    background: #fff;
    padding: 20px;
    border-radius: 6px;
    margin: 10px 30px 10px 30px;
    box-shadow: 0px 10px 10px rgb(0 0 0 / 50%);
    text-align: center;
  }

  .section-3 .col-style-diff {
    background: rgb(255, 217, 0);
    color: #fff;
  }

  .section-3 .col-style-diff a {
    color: #000;
  }

  .section-3 .col-style h4 {
    font-weight: 750;
    margin: 20px 0 20px 0;
  }

  .section-3 .col-style h3 {
    font-size: 3rem;
    font-weight: 750;
  }

  .section-3 .col-style ul {
    list-style-type: none;
    margin: 0;
    padding: 30px 0 30px 0;
    text-align: left;
    display: grid;
    justify-content: center;
    align-items: center;
    font-weight: 800;
  }

  .section-3 .col-style a {
    font-size: 0.8rem;
    font-weight: 750;
    text-decoration: underline !important;
  }

  .section-3 button {
    border: none;
    background: rgb(255, 217, 0);
    color: #000;
    margin: 40px 0 0 0;
    padding: 5px 10px 5px 10px;
    border-radius: 6px;
    /* font-size: 1.2em; */
    font-weight: 750;
  }
</style>