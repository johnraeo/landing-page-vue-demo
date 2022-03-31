<script>
// import { defineComponent } from '@vue/composition-api'

export default {
  name: 'Footer',

}
</script>

<template>
  <footer class="footer-section">
    <div class="container">
      <div class="row">
        <div class="col-md-4">
          <div class="col-style-1">
            <h1>SAMPLE</h1>
          </div>
        </div>
        <div class="col-md-2">
          <div class="col-style-2">
            <h5>Useful Links</h5>
            <ul>
              <li><a href="#">Our Company</a></li>
              <li><a href="#">About Us</a></li>
              <li><a href="#">Services</a></li>
              <li><a href="#">Contact Us</a></li>
              <li><a href="#">FAQ</a></li>
            </ul>
          </div>
        </div>
        <div class="col-md-2">
          <div class="col-style-3">
            <h5>Legal</h5>
            <ul>
              <li><a href="#">Privacy Policy</a></li>
              <li><a href="#">Terms of Service</a></li>
              <li><a href="#">Legal Notice</a></li>
            </ul>
          </div>
        </div>
        <div class="col-md-4">
          <div class="col-style-4">
            <h2>sample.sample@gmail.com</h2>
            <p>Get Connected with us! <span>F</span></p>
          </div>
        </div>
      </div>
      <hr>
      <p class="copyright">&copy; 2021 Sample. All Rights Reserved.</p>
    </div>
  </footer>
</template>

<style scoped>
  .footer-section {
    background: rgb(247, 247, 247);
    padding: 100px 0px 150px 0px;
  }

  .footer-section .col-style-1 h1 {
    font-weight: 900;
  }

  .footer-section .col-style-2 h5 {
    font-weight: 750;
    margin: 0 0 20px 0;
  }

  .footer-section .col-style-2 ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
  }

  .footer-section .col-style-2 ul li {
    margin: 0 0 5px 0;
  }

  .footer-section .col-style-2 ul li a {
    text-decoration: none;
    color: #000;
  }

  .footer-section .col-style-3 h5 {
    font-weight: 750;
    margin: 0 0 20px 0;
  }

  .footer-section .col-style-3 ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
  }

  .footer-section .col-style-3 ul li {
    margin: 0 0 5px 0;
  }

  .footer-section .col-style-3 ul li a {
    text-decoration: none;
    color: #000;
    margin: 20px 0 10px 0;
  }

  .footer-section .col-style-4 h2 {
    /* overflow-wrap: break-word; */
    margin: 0 0 20px 0;
  }

  .footer-section hr {
    border: 1.5px solid black;
    opacity: 1 !important;
  }

  .footer-section .copyright {
    text-align: center;
  }
</style>