<template>
<div>
  <nav class="navbar navbar-expand-lg navbar-dark bg-nav">
    <div class="container bar">
      <a class="brand" href="#">
        <img src="https://avada.theme-fusion.com/fitness/wp-content/uploads/sites/130/2021/04/logo-svg.svg" alt="logo-svg">
      </a>
      <div class="">
        <ul class="navbar-nav">
          <li class="nav-item" v-for="(navigation, index) in navigations" :key="index">
            <a class="nav-link" :href="navigation.link">{{ navigation.text }}</a>
          </li>
          <li>
            <button class="btn" type="button">Schedule a workout</button>
          </li>
          <li>
            <i class="fa-solid fa-magnifying-glass"></i>
          </li>
          <li>
            <i class="fa-solid fa-cart-shopping"></i>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</div>
</template>

<script>
export default {
  name: "Header",
  props: ["navigations"],
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../assets/sass/_vars.scss";


.brand img{
    height: 30px;
    width: 100%;
    margin: 20px 0;
}

.btn{
  background-color: $blue;
  color: $white;
  padding: 8px 24px;
  border-radius: 20px;
  font-size: 14px;
}

li{
  padding: 0 10px;
}

i{
  color: $white;
  line-height: 40px;
}

button{
  font-weight: 500;
}

.fa-magnifying-glass{
  opacity: 0.6;
}

a{
  font-size: 18px;
  font-weight: 500;

}
</style>
