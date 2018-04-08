<template>
  <div class="dragonTiger">
    <div class="container">
      <div class="header clearfix">
        <div class="logoBox">
        </div>
        <div class="moneyBox">
          142,000
        </div>
      </div>
      <div class="main clearfix">
        <div class="bet">
          <div class="tabbar">
            
          </div>
          <div class="betDesk">

          </div>
          <div class="betBoard">

          </div>
          <div class="betRecord">

          </div>
        </div>
        <div class="history">

        </div>
      </div>
    </div>
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


<style scoped>
html, body {
  margin: 0;
  padding: 0;
}
.clearfix:after {
  content: '';
  display: block;
  clear: both;
}
.dragonTiger {
  background: url('../assets/images/longhu_bg.jpg') no-repeat center top;
  font-size: 14px;
}
.dragonTiger .container {
  width: 1200px;
  margin: 0 auto;
}
.dragonTiger .container .header {
  position: relative;
}
.dragonTiger .container .header .logoBox {
  width: 586px;
  height: 96px;
  float: left;
  background: url('../assets/images/logo.png') no-repeat center top;
}
.dragonTiger .container .header .moneyBox {
  width: 274px;
  height: 64px;
  float: right;
  background: url('../assets/images/money.png') no-repeat center top;
  text-align: right;
  padding-right: 86px;
  color: #fff;
  line-height: 57px;
  box-sizing: border-box;
}
.dragonTiger .container .main {
  position: relative;
  top: -26px;
  height: 500px;
  padding: 0 6px;
}
.dragonTiger .container .main .bet {
  float: left;
  width: 836px;
}
.dragonTiger .container .main .bet .tabbar {
  height: 56px;
  background: url('../assets/images/bet_hd_bg.png') no-repeat center top;
}
.dragonTiger .container .main .bet .betDesk {
  height: 315px;
  background: url('../assets/images/bet_bd_bg.png') no-repeat center top;
}
.dragonTiger .container .main .bet .betBoard {
  height: 164px;
  background: url('../assets/images/bet_board_bg.png') no-repeat center top;
}
.dragonTiger .container .main .bet .betRecord {
  height: 110px;
  background: url('../assets/images/betRecord_bg.png') no-repeat center top;
}






</style>
