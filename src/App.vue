<template>
<body>
    <div class="app-container">
      <questionbox/>
    </div>
  </body>

</template>

<script>
import questionbox from '../src/components/QuestionBox.vue'

export default {

  components: {
    questionbox,
  },
};
  




</script>

<style>
* {
    box-sizing: border-box;
    padding: 0;
    margin: 0;
  }
  
  body {
    font-family: Lato;
  }

  .app-container {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100vh; /* 100% da altura da viewport, para centralizar verticalmente */
}
  
  a {
    color: #F5F6F8;
    text-decoration: none;
    font: normal normal normal 16px/19px Lato;
  }
  
  @font-face {
    font-family: Lato;
    src: url('../src/assets/Lato-Bold.ttf');
    font-weight: 400;
    font-display: block;
  }
  
  @font-face {
    font-family: Lato;
    src: url('../src/assets/Lato-Bold.ttf');
    font-weight: 700;
    font-display: block;
  }

</style>
