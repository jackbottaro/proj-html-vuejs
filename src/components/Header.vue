<template>
<div>
  <nav class="navbar navbar-expand-lg navbar-dark bg-nav">
  <div class="container bar">
     <a class="brand" href="#">
      <img src="https://avada.theme-fusion.com/fitness/wp-content/uploads/sites/130/2021/04/logo-svg.svg" alt="logo-svg">
    </a>

    <div class="">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Services
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
            <li><a class="dropdown-item" href="#">All Services</a></li>
            <li><a class="dropdown-item" href="#">Service Single Page</a></li>
          </ul>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            About
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
            <li><a class="dropdown-item" href="#">About Me</a></li>
            <li><a class="dropdown-item" href="#">Our Sponsor</a></li>
            <li><a class="dropdown-item" href="#">Contact</a></li>
          </ul>
          
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Videos
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
            <li><a class="dropdown-item" href="#">All Playlists</a></li>
            <li><a class="dropdown-item" href="#">Playlists Page</a></li>
            <li><a class="dropdown-item" href="#">Video Single page</a></li>
          </ul>
          
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Blog</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Store
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
            <li><a class="dropdown-item" href="#">Simple Product</a></li>
            <li><a class="dropdown-item" href="#">Variable Product</a></li>
          </ul>
          
        </li>
        <li>
          <button class="btn" type="button">Schedule a workout</button>
        </li>
        <li>
          <i class="fa-solid fa-magnifying-glass"></i>
        </li>
        <li>
          <i class="fa-solid fa-cart-shopping"></i>
        </li>
      </ul>
    </div>
  </div>
</nav>
</div>
</template>

<script>
export default {
  name: "Header",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">


.brand img{
    height: 30px;
    width: 100%;
    margin: 20px 0;
}

.btn{
  background-color: #4154ff;
  color: white;
  padding: 8px 24px;
  border-radius: 20px;
  font-size: 14px;
}

li{
  padding: 0 10px;
}

i{
  color: white;
  line-height: 40px;
}
</style>
