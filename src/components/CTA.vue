<template>
<div id="CTA">
  <div class="container">
<h2>“I’ve failed over and over again in my life. And that is why I succeed.”</h2>

  <p>Arcu auctor gravida nisl, congue sit nisi tincidunt eget proin. In lacinia lacus donec sed massa in ipsum eros, tristique. Gravida suspendisse etiam in iaculis</p>
  <button type="button" class="btn">Buy Avada today <i class="fa-solid fa-angle-right"></i></button>
  </div>
  
</div>
</template>

<script>
export default {
  name: "CTA",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
#CTA{
  height: 700px;
  background-color: rgba(255, 255, 255, 0);
    background-image: linear-gradient(0deg, rgba(0,0,0,1) 0%, rgba(0,0,0,0.5) 52%, rgba(0,0,0,0) 100%),url(https://avada.theme-fusion.com/fitness/wp-content/uploads/sites/130/2019/11/banner2@2x.jpg);
    background-position: center center;
    background-repeat: no-repeat;
    background-size: cover;
    text-align: center;
    padding:140px 400px;;
}

h2{
  font-size: 58px;
  color: white;
  margin-bottom: 50px;
}

p{
  font-size: 23px;
  color: #d6d5d8;
  margin-bottom: 50px;

}

.btn{
  padding: 15px 40px;
  border-radius: 50px;
  margin-left: 50px;
  background-color: #4154ff;
  color: white;
  font-weight: 500;
}

.btn:hover{
  background-color: #ff414b;
}

</style>
