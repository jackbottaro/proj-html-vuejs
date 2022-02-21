<template>
<div id="events">
  <div>
    <i class="fa-solid fa-play"></i>
    <h2>Crossfit workout of the day</h2>
    <h5>November 15th, 2019</h5>
    <span>View all videos <i class="fa-solid fa-angle-right"></i>
    </span>
  </div>
</div>
</template>

<script>
export default {
  name: "Events",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../assets/sass/_vars.scss";

#events {
	height: 600px;
	background-color: rgba(255, 255, 255, 0);
	background-image: linear-gradient(151deg, $blue 35%, $red 100%), url(https://avada.theme-fusion.com/fitness/wp-content/uploads/sites/130/2019/11/banner14@2x.jpg);
	background-position: center center;
	background-repeat: no-repeat;
	background-blend-mode: multiply;
	background-size: cover;
	color: white;
	padding: 150px 0;
	text-align: center;
}

h2 {
	font-size: 58px;
}

h5 {
	font-size: 38px;
	color: $yellow;
}

span {
	font-size: 20px;
}

i {
	margin-bottom: 20px;
}


</style>
