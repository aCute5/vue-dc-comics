<template>
  <footer>
    <img src="@/img/dc-logo-bg.png" class="logo-background" alt="" />
    <ul class="nav justify-content-start p-5 footer-ul">
      <li class="nav-item">
        <h2>DC COMICS</h2>
      </li>
      <li class="nav-item">
        <a class="nav-link active" aria-current="page" href="#">Active</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Link</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Link</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Disabled</a>
      </li>
      <h2>SHOP</h2>
      <li class="nav-item">
        <a class="nav-link" href="#">Disabled</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Disabled</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Disabled</a>
      </li>
    </ul>
    <ul class="nav justify-content-start p-5 footer-ul">
      <li class="nav-item">
        <h2>DC COMICS</h2>
      </li>
      <li class="nav-item">
        <a class="nav-link active" aria-current="page" href="#">Active</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Link</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Link</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Disabled</a>
      </li>
      <h2>SHOP</h2>
      <li class="nav-item">
        <a class="nav-link" href="#">Disabled</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Disabled</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Disabled</a>
      </li>
    </ul>
    <ul class="nav justify-content-start p-5 footer-ul">
      <li class="nav-item">
        <h2>DC COMICS</h2>
      </li>
      <li class="nav-item">
        <a class="nav-link active" aria-current="page" href="#">Active</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Link</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Link</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Disabled</a>
      </li>
      <h2>SHOP</h2>
      <li class="nav-item">
        <a class="nav-link" href="#">Disabled</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Disabled</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Disabled</a>
      </li>
    </ul>
    <div class="bottomfooter">
      <button type="button" class="btn p-2 m-5">SIGN UP NOW</button>
      <ul class="nav justify-content-center">
        <li class="nav-item follow-us">FOLLOW US</li>
        <li class="nav-item">
          <img src="@/img/footer-facebook.png" alt="" />
        </li>
        <li class="nav-item">
          <img src="@/img/footer-youtube.png" alt="" />
        </li>
        <li class="nav-item">
          <img src="@/img/footer-twitter.png" alt="" />
        </li>
        <li class="nav-item">
          <img src="@/img/footer-pinterest.png" alt="" />
        </li>
        <li class="nav-item">
          <img src="@/img/footer-periscope.png" alt="" />
        </li>
      </ul>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
$blue-dc: #0282f9;
h2 {
  color: white;
}
footer {
  display: flex;
  flex-wrap: wrap;
  justify-content: flex-start;
  background-image: url("@/img/footer-bg.jpg");
  position: relative;
  height: 50vh;
}
.logo-background {
  position: absolute;
  right: 0;
  height: 110%;
  bottom: 1%;
}
.footer-ul {
  flex-direction: column;
  padding-left: 3rem;
}
footer .bottomfooter {
  background-color: #303030;
  display: flex;
  justify-content: space-between;
  height: 10vh;
  flex-basis: 100%;
  align-items: center;
  z-index: 2;
}
.bottomfooter ul {
  justify-content: space-around;
  gap: 1rem;
  align-items: center;
}
.bottomfooter img {
  padding: 0.4rem;
}
.bottomfooter .follow-us {
  color: $blue-dc;
}
footer .bottomfooter button {
  display: flex;
  justify-content: center;
  color: white;
  align-items: center;
  width: 150px;
  border-radius: 2px;
  height: 60px;
  border: 1px solid $blue-dc;
}
</style>
