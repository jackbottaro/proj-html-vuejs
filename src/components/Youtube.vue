<template>
<div class="youtube">
  <div class="row">
    <div class="col-6">
      <div class="card"></div>
    </div>
    <div class="col-6 text">
      <div class="container">
        <span>Tune up your workouts</span>
      <h4>The best health & fitness advice online</h4>
      <p>Arcu eu facilisi ut quisque placerat nunc habitant. Magna semper mauris, venenatis, leo integer sit pellentesque.</p>
      <button>yotube</button>
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
  margin-bottom: 100px;
}

.card{
    height: 700px;
    background-image: linear-gradient(16deg, rgb(0 0 0 / 76%), rgba(0, 0, 0, 0)), url(https://avada.theme-fusion.com/fitness/wp-content/uploads/sites/130/2019/11/video1@2x.jpg);
    background-position: center center;
    background-repeat: no-repeat;
    background-size: cover;
    border-radius: 0px 4px 40px 0px;
    position: absolute;
    width: 800px;
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
}

h4{
  font-size: 54px;
    line-height: 1.2;
  margin-bottom: 30px;
  margin-top: 30px;


}

p{
  font-size: 20px;
  margin-bottom: 30px;
  color: #333333;

}
</style>
