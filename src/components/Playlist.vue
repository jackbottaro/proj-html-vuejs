<template>
 <div class="playlist">
   <div class="container">
     <div class="row d-flex gx-5">
       <div class="col-6">
         <h4>Featured playlist</h4>
       </div>
       <div class="col-6">
          <span>Read all articles <i class="fa-solid fa-angle-right"></i></span>
       </div>
       <div class="col-4">
         <div class="card">
            <i class="fa-solid fa-play"></i>
           <img src="https://avada.theme-fusion.com/fitness/wp-content/uploads/sites/130/2019/11/video2@2x.jpg" alt="Thighs & glute workout" >
          <div class="text">
            <p class="title">Thighs & glute workout</p>
            <p class="subtitle">Increase you mobility</p>
          </div>
         </div>
       </div>
       <div class="col-4">
         <div class="card">
           <i class="fa-solid fa-play"></i>
           <img src="https://avada.theme-fusion.com/fitness/wp-content/uploads/sites/130/2019/11/video7@2x.jpg" alt="Lift, firm & perk up" >
          <div class="text">
            <p class="title">Lift, firm & perk up</p>
            <p class="subtitle">Feel young again</p>
          </div>
         </div>
       </div>
       <div class="col-4">
         <div class="card">
           <i class="fa-solid fa-play"></i>
           <img src="https://avada.theme-fusion.com/fitness/wp-content/uploads/sites/130/2019/12/video9@2x.jpg" alt="Slim & trim your waist" >
          <div class="text">
            <p class="title">Slim & trim your waist</p>
            <p class="subtitle">Shed those extra pounds</p>
          </div>
         </div>
       </div>
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
.playlist{
  height: 500px;

padding: 80px 0px;
margin-bottom: 100px;
}


// CARD
.card{
  background-color: transparent;
  border: 0;
  text-align: center;
  margin-top: 40px;
  position: relative;

}
.card img{
  height: 250px;
  width: 100%;
  background-size: cover;
    border-radius: 4px 4px 40px;
  margin-bottom: 20px;
}

.title{
  font-weight: 500;
  font-size: 23px;
  margin-bottom: 0;
}

.subtitle{
  color: #4154ff;
  font-weight: 500;
  font-size: 17px;
  


}

h4{
  font-size: 27px;
}

.videos{
  text-align: right;
}

.fa-play{
    position: absolute;
    margin-left: auto;
    margin-right: auto;
    left: 0;
    right: 0;
    top: 88px;
    font-size: 20px;
    height: 60px;
    width: 60px;
    line-height: 60px;
}

span{
  display: flex;
  justify-content: end;
  align-items: baseline;
  font-weight: 600;
  font-size: 18px;
}
</style>
