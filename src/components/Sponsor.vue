<template>
<div>
  <div class="container">
    <div class="row">
      <div class="col">
        <div class="sponsor-box">
          <img src="https://avada.theme-fusion.com/fitness/wp-content/uploads/sites/130/2019/11/sponsor-1@2x.png" alt="Yoga Studio Logo">
          <p>Tristique aliquam in nullam habitasse nunc, amet vel consectetur. Nulla in suspendisse dolor, aliquet.</p>
          <span>Visit Yoga Studio <i class="fa-solid fa-angle-right"></i>
          </span>
        </div>
      </div>
      <div class="col">
        <div class="sponsor-box">
          <img src="https://avada.theme-fusion.com/fitness/wp-content/uploads/sites/130/2019/11/sponsor-2@2x.png" alt="Fitness Center Logo">
          <p>Feugiat etiam dui mauris pharetra mauris sed pharetra. Convallis sapien ornare cras faucibus nulla porta dui a.</p>
          <span>Join Fitness Center <i class="fa-solid fa-angle-right"></i>
          </span>
        </div>
      </div>
      <div class="col">
        <div class="sponsor-box">
          <img src="https://avada.theme-fusion.com/fitness/wp-content/uploads/sites/130/2019/11/sponsor-3@2x.png" alt="FC Logo">
          <p>Nisl at quam adipiscing montes, nec, adipiscing commodo aliquam tincidunt. Ligula in habitant et sagittis imperdiet.</p>
          <span>Learn about FC <i class="fa-solid fa-angle-right"></i>
          </span>
        </div>
      </div>
      <div class="col">
        <div class="sponsor-box">
          <img src="https://avada.theme-fusion.com/fitness/wp-content/uploads/sites/130/2019/11/sponsor-4@2x.png" alt="Power Gym Logo">
          <p>Proin in viverra maecenas et mattis ut nibh enim. Gravida ultricies mi porta lacus. Et posuere velit sed nec eleifend.</p>
          <span>Visit Power Gym <i class="fa-solid fa-angle-right"></i>
          </span>
        </div>
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: "Sponsor",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../assets/sass/_vars.scss";

.sponsor-box {
	height: 300px;
	width: 290px;
	text-align: center;
	margin: 100px 0;
	cursor: pointer;
}

img {
	height: 90px;
	margin-bottom: 30px;
}

p {
	font-size: 19px;
	color: $gray;
	margin-bottom: 30px;
}

span {
	font-weight: 600;
}


</style>
