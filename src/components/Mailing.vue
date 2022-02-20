<template>
  <div class="spotlight">
    <div class="container">
<div class="row ">
        <div class="col-8 text ">
          <p id="subtitle">Join our mailing list today</p>
          <h2>Insider offers & flash sales in your inbox every week.</h2>
          <div class="d-flex mail">
             <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="Insert your email...">
             <button type="button" class="btn">Subscribe</button>
          </div>
          <p>Curabitur non nulla sit amet nisl tempus convallis quis ac lectus dolor sit amet, consectetur adipiscing elit sed porttitor lectus.</p>
        </div>
        <div class="col"></div>
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

.spotlight{
  height: 600px;
    background-color: black;
    background-position: center top;
    background-repeat: no-repeat;
    border-width: 0px;
    border-style: solid;
    background-size: cover;background-image: linear-gradient(90deg, black 45%,rgba(6,6,7,0) 75%),url("https://avada.theme-fusion.com/fitness/wp-content/uploads/sites/130/2019/11/banner1@2x.jpg");

}

.text{
  color: white;
  margin-top: 100px;
}

h2{
  font-size: 58px;
}

p{
  font-size: 23px;
  color: #ffffff;
  opacity: 0.8;
}

#subtitle{
  color: #ff414b;
  font-weight: 600;
  font-size: 28px;
}

.form-control{
  padding: 0.8rem 0.75rem;
    font-size: 1rem;
    border-radius: 50px;
}

.btn{
  padding: 10px 100px;
  border-radius: 50px;
  margin-left: 50px;
  background-color: #4154ff;
  color: white;
  font-weight: 500;
}

.btn:hover{
  background-color: #ff414b;
}

.mail{
  margin: 50px 0;
}
</style>
