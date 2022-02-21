<template>
  <div class="spotlight">
    <div class="container">
      <div class="row ">
        <div class="col text ">
          <p id="subtitle">Certified fitness professional</p>
          <h2>Take control of your healt</h2>
          <p>Curabitur non nulla sit amet nisl tempus convallis quis ac lectus dolor sit amet.</p>
          <a href="#" class="blue">
            <i class="fab fa-youtube"></i> Visit my YouTube channel </a>
          <a href="#" class="white"> Buy Avada today <i class="fa-solid fa-angle-right"></i>
          </a>
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
	height: 700px;
	background: linear-gradient(150deg, $blue 0%, $blod-red 100%);
	padding-bottom: 150px;
}

.text {
	color: $white;
	margin-top: 100px;
}

h2 {
	font-size: 56px;
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
	font-size: 23px;
}

a {
	padding: 17px 40px;
	border-radius: 50px;
	color: $white;
	font-weight: 500;
	font-size: 18px;
	width: 100%;
	display: inline-block;
	text-align: center;
	margin-bottom: 30px;
}

.blue {
	background-color: $blue;
}

a:hover {
	background-color: $red;
	color: $white;
}

.white {
	background-color: $white;
	color: $black;
}


</style>
