<script>
// import { defineComponent } from '@vue/composition-api'

export default {
  name: 'Section2',
}
</script>

<template>
  <section class="section-2">
    <div class="container">
      <h2>Want to Start A New Project</h2>
      <h2>With Us? Let's Start!</h2>
      <button>Contact Now!</button>
    </div>
  </section>  
</template>

<style scoped>
  .section-2 {
    background: rgb(247, 247, 247);
    padding: 150px 0 150px 0;
    border-bottom-left-radius: 100% 50%;
  	border-bottom-right-radius: 100% 50%;
    text-align: center;
    margin: 0 0 100px 0;
  }

  .section-2 h2 {
    font-weight: 900;
  }

  .section-2 button {
    border: none;
    background: rgb(255, 217, 0);
    color: #000;
    margin: 40px 0 0 0;
    padding: 10px 10px 10px 10px;
    border-radius: 10px;
    font-size: 1.2em;
    font-weight: 750;
  }
</style>