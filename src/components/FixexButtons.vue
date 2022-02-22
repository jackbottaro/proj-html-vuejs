<template>
   <div class="buttons">
     <div class="button">
       <i class="fa-solid fa-images"></i>
       <span>Prebuilts</span>
     </div>
     <div class="button">
       <i class="fa-solid fa-cart-shopping"></i>
       <span>Buy Now</span>
     </div>
   </div>
</template>

<script>
export default {
  name: "Articles",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../assets/sass/_vars.scss";

.buttons {
	position: fixed;
	top: 170px;
	right: 20px;
	cursor: pointer;
}

.button {
	text-align: center;
	height: 66px;
	width: 66px;
	background-color: $white;
	padding: 10px 0;
	border-radius: 8px;
	box-shadow: 0 0 25px 5px rgba(0, 0, 0, .2);
	display: flex;
	flex-direction: column;
	justify-content: space-between;
	margin-bottom: 8px;
}

span {
	font-size: 14px;
	line-height: 1;
	color: $gray;
	font-weight: 700;
	font-family: inherit;
	letter-spacing: normal;
}

.fa-images,
.fa-cart-shopping {
	color: $gray;
	font-size: 23px;
}


</style>
