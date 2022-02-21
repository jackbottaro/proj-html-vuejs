<template>
<div id="plans">
  <div class="container">
    <div class="row gx-5">
      <div class="col-4">
        <div class="cart">
          <i class="fa-solid fa-heart-pulse"></i>
          <h4>Team training</h4>
          <h5>Find a partner</h5>
          <p>Vestibulum, curabitur eu sem nibh ultrices sit nulla adipiscing. Nisl sit fames amet senectus eget sed duis vehicula. Tristique.</p>
          <a href="#">
            <span>Find a partner <i class="fa-solid fa-angle-right"></i>
            </span>
          </a>
        </div>
      </div>
      <div class="col-4">
        <div class="cart">
          <i class="fa-solid fa-dumbbell"></i>
          <h4>Crossfit workout</h4>
          <h5>Push your limits</h5>
          <p>Vestibulum, curabitur eu sem nibh ultrices sit nulla adipiscing. Nisl sit fames amet senectus eget sed duis vehicula. Tristique.</p>
          <a href="#">
            <span>Learn about Crossfit <i class="fa-solid fa-angle-right"></i>
            </span>
          </a>
        </div>
      </div>
      <div class="col-4">
        <div class="cart">
          <i class="fa-solid fa-person-walking"></i>
          <h4>Weight loss plan</h4>
          <h5>Shed those pounds</h5>
          <p>Vestibulum, curabitur eu sem nibh ultrices sit nulla adipiscing. Nisl sit fames amet senectus eget sed duis vehicula. Tristique.</p>
          <a href="#">
            <span>Schedule a workout <i class="fa-solid fa-angle-right"></i>
            </span>
          </a>
        </div>
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: "Plans",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../assets/sass/_vars.scss";

#plans {
	background-color: $black;
	padding: 100px 0;
}

.cart {
	height: 570px;
	width: 420px;
	border: 5px solid $blue;
	border-radius: 8px;
	text-align: center;
	color: white;
	padding: 70px 50px;
	// background-color: red;
}

.cart:hover {
	transition: 0.5s;
	transform: scale(1.03);
}

h4 {
	font-size: 28px;
	font-weight: 600;
}

h5 {
	color: $yellow;
	font-size: 23px;
	margin-bottom: 50px;
}

span {
	font-weight: 600;
	font-size: 18px;
}

p {
	font-size: 20px;
	line-height: 28px;
	margin-bottom: 50px;
}

.fa-dumbbell,
.fa-heart-pulse,
.fa-person-walking {
	font-size: 50px;
	margin-bottom: 50px;
}
</style>
