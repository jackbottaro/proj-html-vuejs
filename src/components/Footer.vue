<template>
  <div id="footer">
      <div class="container ">
        <div class="row gx-5 data">
          <div class="col info">
            <img src="https://avada.theme-fusion.com/fitness/wp-content/uploads/sites/130/2021/04/logo-svg.svg" alt="Logo">
            <p>Ac aliquam neque sagittis diam faucibus vitae purus turpis phasellus. Pellentesque consectetur amet purus ultrices mauris.</p>
            <div class="social">
              <i class="fa-brands fa-facebook-f"></i>
              <i class="fa-brands fa-twitter"></i>
              <i class="fa-brands fa-instagram"></i>
              <i class="fa-brands fa-youtube"></i>
              <i class="fa-brands fa-linkedin-in"></i>
            </div>
          </div>
          <div class="col post">
            <h5>RECENT POST</h5>
            <ul>
              <li v-for="(foot, index) in footer" :key="index"><i class="fa-solid fa-angle-right"></i><a :href="foot.link"><span>{{ foot.text }}</span></a></li>
            </ul>
          </div>
          <div class="col contact">
            <h5>CONTACT INFORMATIONS</h5>
            <address>4746 Tipple Road Michigan 48449</address>
            <div class="number">
              <span>Mobile : 1.800.000.0000</span>
              <br>
              <span>Email : info@your-company.com</span>
            </div>
          </div>
        </div>
      </div>

      <hr>
      <div class="sub-footer">
        <span>© Copyright 2012 - 2022 | Avada Theme by <a href="#">ThemeFusion</a> | All Rights Reserved | Powered by <a href="#">WordPress</a></span>
      </div>
  </div>
</template>

<script>
export default {
  name: "Header",
  props: ["footer"],
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../assets/sass/_vars.scss";

#footer{
  background-color: $black;
  padding-top: 150px;
  
  color: $white;
  
}

.data{
  padding-bottom: 50px;
}
.col{
  text-align: center;
}

h5{
  margin-bottom: 30px;
  font-size: 23px;

}

// INFO
img{
  margin-bottom: 30px;
}

.info p{
  font-size: 20px;
  margin-bottom: 30px;

}

.social{
  color: $red;
}
.social i{
  margin: 10px;
  cursor: pointer;
}

// POST
h5{
  margin-bottom: 30px;
  font-size: 23px;

}

.post i{
  margin-right: 5px;
}

.post span{
  font-size: 20px;
}

.post li{
  margin-bottom: 20px;
}

.contact address{
  font-size: 23px;
  color: $gray;
  opacity: 0.8;
}

.number span{
  font-size: 20px;
}

// SUB FOOTER

.sub-footer{
  padding: 30px;
  text-align: center;
  color: $gray;
  font-size: 17px;
}

.sub-footer a{
  color: $white;
}
</style>
