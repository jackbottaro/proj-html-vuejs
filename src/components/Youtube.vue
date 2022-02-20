<template>
<div class="youtube container-fluid">
  <div class="row">
    <div class="col-6">
      <div class="card"></div>
    </div>
    <div class="col-6 text">
      <div class="container">
        <span>Tune up your workouts</span>
      <h4>The best health & fitness advice online</h4>
      <p>Arcu eu facilisi ut quisque placerat nunc habitant. Magna semper mauris, venenatis, leo integer sit pellentesque.</p>
      <a href="#">
        <i class="fab fa-youtube"></i> 
        Visit my YouTube channel
      </a>
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: "Youtube",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.youtube{
  position: relative;
  margin-bottom: 200px;
}

.card{
    height: 780px;
    background-image: linear-gradient(16deg, rgb(0 0 0 / 76%), rgba(0, 0, 0, 0)), url(https://avada.theme-fusion.com/fitness/wp-content/uploads/sites/130/2019/11/video1@2x.jpg);
    background-position: center center;
    background-repeat: no-repeat;
    background-size: cover;
    border-radius: 0px 4px 40px 0px;
    position: absolute;
    width: 850px;
    top: -69px;
    border: 0;
    left: 0;
}


.text{
  padding: 80px;
}

span{
  font-size: 28px;
  color: #4154ff;
  font-weight: 600;
}

h4{
  font-size: 62px;
    line-height: 74px;
  margin-bottom: 30px;
  margin-top: 30px;
  color: #060607;


}

p{
  font-size: 23px;
  margin-bottom: 50px;
  color: #7e7887;

}

.row {
    margin-right: 0;
    margin-left: 0;
}

button.btn.cancel::before {
   font: var(--fa-font-solid);
   font-weight: 900;
   font-family: Font Awesome 6 Free;
    content: "\f167";
}

a{
  background-color: #f5000c;
  padding: 15px 30px;
  border-radius: 50px;
  color: white;
  font-weight: 500;
  font-size: 18px;
  

}

i{
  margin-right: 10px;
}
</style>
