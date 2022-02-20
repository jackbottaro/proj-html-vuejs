<template>
  <div class="spotlight">
    <div class="container">
<div class="row ">
        <div class="col-8 text ">
          <p id="subtitle">Certified fitness professional</p>
          <h2>Take control of your healt</h2>
          <p>Curabitur non nulla sit amet nisl tempus convallis quis ac lectus dolor sit amet.</p>
        </div>
        <div class="col"></div>
      </div>
    </div>
      
  </div>
</template>

<script>
export default {
  name: "Spotlight",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.spotlight{
  height: 600px;
    background-color: black;
    background-position: center top;
    background-repeat: no-repeat;
    border-width: 0px;
    border-style: solid;
    background-size: cover;background-image: linear-gradient(90deg, black 45%,rgba(6,6,7,0) 75%),url("https://avada.theme-fusion.com/fitness/wp-content/uploads/sites/130/2020/02/slider82x-scaled.jpg");

}

.text{
  color: white;
  margin-top: 100px;
}

h2{
  font-size: 56px;
}

p{
  font-size: 25px;
  color: #ffffff;
  opacity: 0.8;
}

#subtitle{
  color: #ff414b;
  font-weight: 600;
  font-size: 23px;
}
</style>
