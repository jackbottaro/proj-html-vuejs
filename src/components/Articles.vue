<template>
 <div class="playlist">
   <div class="container">
     <div class="row d-flex gx-5">
       <div class="col-6">
         <h4>Latest articles</h4>
       </div>
       <div class="col-6">
          <span>Read all articles <i class="fa-solid fa-angle-right"></i></span>
       </div>
       <div class="col-4">
         <div class="card">
           <img src="https://avada.theme-fusion.com/fitness/wp-content/uploads/sites/130/2019/11/blog4@2x-800x515.jpg" alt="Thighs & glute workout" >
          <div class="text">
            <p class="title">Thighs & glute workout</p>
            <p class="subtitle">By <a href="#">admin</a> | November 26th, 2019 | <a href="#">Gym</a></p>
          </div>
         </div>
       </div>
       <div class="col-4">
         <div class="card">
           <img src="https://avada.theme-fusion.com/fitness/wp-content/uploads/sites/130/2019/11/blog1@2x-800x515.jpg" alt="Ultimate cardio workout" >
          <div class="text">
            <p class="title">Ultimate cardio workout</p>
            <p class="subtitle">By <a href="#">admin</a> | November 26th, 2019 | <a href="#">Gym</a></p>

          </div>
         </div>
       </div>
       <div class="col-4">
         <div class="card">
           <img src="https://avada.theme-fusion.com/fitness/wp-content/uploads/sites/130/2019/11/blog3@2x-800x515.jpg" alt="New juices available now" >
          <div class="text">
            <p class="title">New juices available now</p>
            <p class="subtitle">By <a href="#">admin</a> | November 26th, 2019 | <a href="#">Gym</a></p>

          </div>
         </div>
       </div>
     </div>
   </div>
 </div>
</template>

<script>
export default {
  name: "Articles",
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

  margin-top: 40px;

}
.card img{
  height: 250px;
  width: 100%;
  background-size: cover;
  margin-bottom: 20px;
}
.text{
  margin-left: 20px;
}
.title{
  font-weight: 500;
  font-size: 28px;
  margin-bottom: 0;
}

.subtitle{
  color: #7e7887;
  font-weight: 400;
  font-size: 18px;
  


}

h4{
  font-size: 27px;
}
a{
  color: black;
}
.videos{
  text-align: right;
}

span{
  display: flex;
  justify-content: end;
  align-items: baseline;
  font-weight: 600;
  font-size: 18px;
}
</style>
