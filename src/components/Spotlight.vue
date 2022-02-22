<template>
  <div class="spotlight">
    <div class="container">
      <div class="row ">
        <div class="col-9 text ">
          <p id="subtitle">Certified fitness professional</p>
          <h2>Take control of your healt</h2>
          <p>Curabitur non nulla sit amet nisl tempus convallis quis ac lectus dolor sit amet.</p>
          <a href="#" class="blue">
            <i class="fab fa-youtube"></i> Visit my YouTube channel </a>
          <a href="#" class="white"> Buy Avada today <i class="fa-solid fa-angle-right"></i>
          </a>
        </div>
		<div class="col play">
			<i class="fa-solid fa-play"></i>
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
@import "../assets/sass/_vars.scss";

.spotlight {
	height: 600px;
	background-color: black;
    background-position: center top;
    background-repeat: no-repeat;
    border-width: 0px;
    border-style: solid;
    background-size: cover;background-image: linear-gradient(90deg, black 45%,rgba(6,6,7,0) 75%),url("https://avada.theme-fusion.com/fitness/wp-content/uploads/sites/130/2020/02/slider82x-scaled.jpg");
}

.text {
	color: $white;
	margin-top: 100px;
}

h2 {
	font-size: 75px;
}

p {
	font-size: 25px;
	color: $white;
	opacity: 0.8;
	margin-bottom: 30px;
}

#subtitle {
	color: $red;
	font-weight: 600;
	font-size: 27px;
}

a {
	padding: 17px 40px;
	border-radius: 50px;
	color: $white;
	font-weight: 500;
	font-size: 18px;
	display: inline-block;
	text-align: center;
	margin-bottom: 30px;
	margin-right: 20px;
}

.blue {
	background-color: $blue;
}

a:hover {
	background-color: $red;
	color: $white;
}

.white:hover{
	background-color: white;
	color: $black;
	border: 3px solid white;

} 
.white {
	background-color: transparent;
	color: $black;
	border: 3px solid $gray;
	color: white;
}

// PLAY

.play i{

    position: absolute;
    left: 0;
    right: 0;
    top: 0;
    bottom: 0;
    margin: auto;

}
.play i:hover{
	color: $red;
}
.play{
	position: relative;
}
</style>
