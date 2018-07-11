<template>
    <!--<div class="box">
      <div class="first-face">
        <span class="pip"></span>
      </div>


     <div class="second-face">
        <span class="pip"></span>
        <span class="pip"></span>
      </div>
     <div class="third-face">
        <span class="pip"></span>
        <span class="pip"></span>
        <span class="pip"></span>
      </div>
      <div class="fourth-face">
        <div class="column">
          <span class="pip"></span>
          <span class="pip"></span>
        </div>
        <div class="column">
          <span class="pip"></span>
          <span class="pip"></span>
        </div>
      </div>
      <div class="fifth-face">
        <div class="column">
          <span class="pip"></span>
          <span class="pip"></span>
        </div>
        <div class="column">
          <span class="pip"></span>
        </div>
        <div class="column">
          <span class="pip"></span>
          <span class="pip"></span>
        </div>
      </div>
      <div class="sixth-face">
        <div class="column">
          <span class="pip"></span>
          <span class="pip"></span>
          <span class="pip"></span>
        </div>
        <div class="column">
          <span class="pip"></span>
          <span class="pip"></span>
          <span class="pip"></span>
        </div>
      </div>
    </div>-->
  <div class="box">
      <div class="header">header</div>
      <div class="body">
        <div class="left">left</div>
        <div class="middle">middle</div>
        <div class="right">right</div>
      </div>
      <div class="footer">footer</div>
  </div>

</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

/*  .first-face {
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .second-face {
    display: flex;
    justify-content: space-between;
  }

  .second-face .pip:nth-of-type(2) {
    align-self: flex-end;
  }

  .third-face {
    display: flex;
    justify-content:space-between;
  }

  .third-face .pip:nth-of-type(2) {
    align-self: center;
  }

  .third-face .pip:nth-of-type(3) {
    align-self: flex-end;
  }

  .fourth-face, .sixth-face {
    display:flex;
    justify-content: space-between;
  }

  .fourth-face .column, .sixth-face .column {
      display:flex;
      flex-direction:column;
      justify-content: space-between;
  }

  .fifth-face {
    display:flex;
    justify-content: space-between;
  }

  .fifth-face .column {
      display:flex;
      flex-direction: column;
      justify-content: space-between;
  }

  .fifth-face .column:nth-of-type(2) {
      align-self: center;
  }

  !* OTHER STYLES *!

  * {
    box-sizing: border-box;
  }

  html, body {
    height: 100%;
  }

  .box {
    display: flex;
    align-items: center;
    justify-content: center;
    vertical-align: center;
    flex-wrap: wrap;
    align-content: center;
    font-family: 'Open Sans', sans-serif;

    background: linear-gradient(top, #222, #333);
  }

  [class$="face"] {
    margin: 16px;
    padding: 4px;

    background-color: #e7e7e7;
    width: 104px;
    height: 104px;
    object-fit: contain;

    box-shadow:
      inset 0 5px white,
      inset 0 -5px #bbb,
      inset 5px 0 #d7d7d7,
      inset -5px 0 #d7d7d7;

    border-radius: 10%;
  }

  .pip {
    display: block;
    width: 24px;
    height: 24px;
    border-radius: 50%;
    margin: 4px;

    background-color: #333;
    box-shadow: inset 0 3px #111, inset 0 -3px #555;
  }*/

.box{
  display: flex;
  flex-flow: column nowrap;
  height: 100Vh;
  color:#ffffff;
  font-size: 20px;
}
.header{
  flex:1;
  background: grey;

}
.body{
  display: flex;
  flex: 30;
  flex-flow: row nowrap;
  background: lightblue;
}
.body .left{
  flex:2;
  background: lightcoral;
}
.body .middle{
  flex:4;
  background: lightgreen;

}
.body .right{
  flex:2;
  background: lightsalmon;

}
.footer{
  flex:1;
  background: lightslategray;

}



</style>
