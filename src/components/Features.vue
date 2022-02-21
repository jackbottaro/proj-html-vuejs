<template>
 <div class="features ">
   <div class="">
     <div class="container position">
        <div class="row ">
    <div class="col-4 card box-1">
      
      <p>Crossfit workout</p>
      <p id="subtitle">Push your limits</p>
    </div>
    <div class="col-4 card box-2">
      
      <p>New gym apparel</p>
      <p id="subtitle">Look good, feel good</p>
    </div>
    <div class="col-4 card box-3">
      
      <p>Team training</p>
      <p id="subtitle">Find a partner</p>
    </div>
  <div class="col-12">
    <p id="quote">“How you respond to the challenge in the second half will determine what you become after the game, whether you are a winner or a loser.”</p>
  </div>
    <div class="col-12 about">
      <img src="https://avada.theme-fusion.com/fitness/wp-content/uploads/sites/130/2020/03/avatar-1@2x.jpg" alt="">
      <span id="author">Brad Johnson </span>
      <span id="location">Las Vegas</span>
    </div>
  </div>
     </div>
  
  
   </div>

 </div>
</template>

<script>
export default {
  name: "Features",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.features{
  height: 1000px;
background: linear-gradient(150deg, #0316d8 0%, #d8000e 100%);
position: relative;

}

.position{
  position: absolute;
margin-left: auto;
margin-right: auto;
left: 0;
right: 0;
top: -90px;

}
.card{
  height: 450px;
  width: 400px;
  border-radius: 4px 4px 40px;
  padding: 30px;
  display: flex;
  justify-content: end;
    background-position: left top;
  background-position: left top;
    background-repeat: no-repeat;
    background-size: cover;
    border: 0;
   margin: 0 20px;
  box-shadow: 0 0 25px 5px rgba(0,0,0,.2);

}
.box-1{
  background-image: linear-gradient(360deg, rgb(0 0 0 / 76%), rgba(0, 0, 0, 0)), url(https://avada.theme-fusion.com/fitness/wp-content/uploads/sites/130/2019/11/service6@2x.jpg);
}

.box-2{
  background-image: linear-gradient(360deg, rgb(0 0 0 / 76%), rgba(0, 0, 0, 0)), url(https://avada.theme-fusion.com/fitness/wp-content/uploads/sites/130/2019/11/box1@2x.jpg);
}

.box-3{
  background-image: linear-gradient(360deg, rgb(0 0 0 / 76%), rgba(0, 0, 0, 0)), url(https://avada.theme-fusion.com/fitness/wp-content/uploads/sites/130/2019/11/box3@2x.jpg);
}
p{
  font-size: 23px;
  font-weight: 600;
  color: white;
  margin-bottom: 0;
}

#subtitle{
  color: #fff941;
}

#quote{
      padding: 66px 111px;
    text-align: center;
    font-size: 48px;
}

// ABOUT SECTION
.about img{
  border-radius: 50%;
  height: 60px;
  width: 60px;
  margin-right: 20px;
}

.about{
  color: white;
  text-align: center;
}

#author{
  font-weight: 600;
  margin-right: 20px;
  font-size: 21px;
}

#location{
  font-weight: 400;
font-size: 21px;
color: #d5d4d7;

}
</style>
