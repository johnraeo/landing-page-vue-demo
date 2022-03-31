<script>
// import { defineComponent } from '@vue/composition-api'

export default {
 name: 'Header',
}
</script>

<template>
  <header class="header-section">
    <div class="header-section-1">
      <h2>We bring solutions to</h2>
      <h2>make life <span>easier</span></h2>
      <!-- <div class="arrow bounce"> -->
        <a href="#section-1"><span class="arrow down"></span></a>
      <!-- </div>   -->
    </div>
    <div class="header-section-2">
      <div class="container">
        <div class="row">
          <div class="col-md-3">
            <div class="col-style">
              <img src="../../assets/headerpic1.PNG" alt="header pic 1">
              <h3>Software Dev</h3>
              <div class="content">
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. 
                  Saepe nemo nihil nobis enim, repellendus iure commodi optio 
                  aliquid error repellat esse dolorem facere quasi soluta fuga 
                  ipsam repudiandae libero aliquam.
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores ratione, excepturi aliquid quod consequatur architecto soluta ipsam eos placeat minima deserunt libero omnis cum nesciunt vel illum deleniti odio esse.
                  Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ut quaerat, facilis quidem non at odio tempore optio voluptas sit explicabo totam sint neque dolorem eaque, veniam iure. Vero, assumenda quod.</p>
              </div>
              <button>See more ></button>
            </div>
          </div>
          <div class="col-md-3">
            <div class="col-style">
              <img src="../../assets/headerpic2.PNG" alt="header pic 2">
              <h3>Web Dev</h3>
              <div class="content">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                  Esse harum aspernatur est iusto quas, aliquam, expedita 
                  tempore culpa magnam distinctio nisi voluptatum, rerum rem 
                  delectus animi minima quae et quis.</p>
              </div>
              <button>See more ></button>
            </div>
          </div>
          <div class="col-md-3">
            <div class="col-style">
              <img src="../../assets/headerpic3.PNG" alt="header pic 3">
              <h3>UI/UX Design</h3>
              <div class="content">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                  Molestias veniam sequi pariatur, quo recusandae praesentium 
                  animi veritatis fuga alias fugiat adipisci obcaecati, 
                  nostrum voluptatum est facere, expedita deserunt itaque aspernatur.</p>
              </div>
              <button>See more ></button>
            </div>
          </div>
          <div class="col-md-3">
            <div class="col-style">
              <img src="../../assets/headerpic4.PNG" alt="header pic 4">
              <h3>Mobile Dev</h3>
              <div class="content">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                  Eum qui pariatur repellat provident voluptatem laboriosam
                  earum consectetur architecto? Quod veniam harum dolores
                  praesentium illum! Quibusdam blanditiis tempore voluptatem</p>
              </div>
              <button>See more ></button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<style scoped>
  /* Header Section */
  .header-section {
    /* background: linear-gradient(to bottom, lightblue, #fff); */
    background: #fff;
    height: 100vh;
    background-repeat: no-repeat;
    background-size: cover;
  }


  /* Header Section 1 */
  .header-section-1 {
    background: rgb(247, 247, 247);
    padding: 100px 0 300px 0;
    border-bottom-left-radius: 100% 50%;
  	border-bottom-right-radius: 100% 50%;
		position: relative;
    text-align: center;
  }

  .header-section-1 h2 {
    font-size: 3rem;
    /* text-align: center; */
  }

  .header-section-1 h2:nth-child(2) {
    font-weight: 650;
  }

  .header-section-1 span {
    color: rgb(255, 217, 0);
  }

  .header-section-1 .arrow {
    width: 100px;
    height: 100px;
    margin: 20px;
    display: inline-block;
    position: relative;
  }

  .header-section-1 .arrow:hover {
    -moz-animation: bounce 2s infinite;
    -webkit-animation: bounce 2s infinite;
    animation: bounce 2s infinite;
    cursor: pointer;
  }

  @keyframes bounce {
    0%, 20%, 50%, 80%, 100% {
      transform: translateY(0);
    }
    40% {
      transform: translateY(-30px);
    }
    60% {
      transform: translateY(-15px);
    }
  }

  .header-section-1 .arrow::before {
    content: '';
    display: block;
    width: 30px;
    height: 30px;
    top: 50%;
    left: 50%;
    border-style: solid;
    border-color: rgb(255, 217, 0);
    border-width: 5px 5px 0 0;
    position: absolute;
    transform-origin: 50% 50%;
  }

  .header-section-1 .arrow::after {
    content: '';
    display: block;
    top: 50%;
    left: 50%;
    border-style: solid;
    border-color: rgb(255, 217, 0);
    position: absolute;
    transform-origin: 50% 50%;
  }

  .header-section-1 .arrow.down::before {
    transform: rotate(135deg); 
    margin: -20px 0 0 -15px;
  }

  .header-section-1 .arrow.down::after {
    width: 0;
    height: 40px;
    border-width: 0 5px 0 0;
    transform: translate(-3px, -26px);
  }


  /* Header Section 2 */
  .header-section-2 {
    position: absolute; 
    left: 0; 
    right: 0;
    top: 50vmin;
    margin-left: auto; 
    margin-right: auto;
    padding: 10px;
    text-align: center;
    width: 100%; /* Need a specific value to work */
  }

  .header-section-2 .col-style h3 {
    font-weight: 800;
  }

  .header-section-2 .col-style {
    background: #fff;
    padding: 20px;
    border-radius: 10px;
    margin: 10px 10px 10px 10px;
    box-shadow: 0px 10px 10px rgb(0 0 0 / 50%);
    height: 100%;
  }

  .header-section-2 .col-style img {
    width: 25%;
    padding: 0 0 20px 0;
    height: 100px;
    object-fit: contain;
  }

  .header-section-2 .col-style .content {
    height: 150px;
    overflow: hidden;
  }

  .header-section-2 .col-style button {
    border: none;
    background: none;
    color: rgb(255, 217, 0);
    margin: 20px 0 0 0;
    font-size: 1.2em;
  }



  @media (min-width: 1200px) {
    .header-section-2 {
      top: 55vmin;
    }
  }
  /* Media at max-width 770px */
  @media (max-width: 770px) {

    .header-section {
      /* background: linear-gradient(to bottom, lightblue, #fff); */
      height: auto;
    }

    .header-section-1 {
      padding: 100px 0 100px 0;
    }

    .header-section-2 {
      position: relative; 
      top: 0vmin;
    }

    .header-section-2 .col-style {
      height: auto;
    }

  }

  
</style>