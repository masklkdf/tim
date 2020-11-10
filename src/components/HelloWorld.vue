<template>
  <div class="login">
    <div class="left">
      <div></div>
    </div>
    <div class="right"></div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.login {
  width: 45%;
  height: 70%;
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
  display: flex;
  border-radius: 5px 5px 0 5px;
  box-shadow: 2px 2px 2px 1px rgba(0, 0, 0, 0.2),
    -2px -2px 2px 1px rgba(0, 0, 0, 0.2);
}
.login .left {
  width: 60%;
  border-top-left-radius: 5px;
  border-bottom-left-radius: 5px;
  background: url("../assets/images/login_welcome.svg") no-repeat;
}
.login .right {
  width: 40%;
  background-color: blue;
  border-top-right-radius: 5px;
}
</style>
