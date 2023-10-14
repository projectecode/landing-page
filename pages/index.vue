<template>
  <TheHeader />
  <div class="jumbotron">
    <div class="row">
      <div class="col-md-12" style="text-align: center;">
        <div class="container">
          <h1 class="mt-5">Super fast... Super customizable!</h1>
          <hr class="my-4" />
          <p class="lead">
            Order ahead for pickup or let us deliver to your location..
          </p>
          <div role="button" class="menu-type-btn">
            <img
              src="https://s.svgbox.net/materialui.svg?ic=shopping_bag&fill=dd0031"
              width="28"
              height="28"
            />
            <strong>Pickup</strong>
          </div>
          <div role="button" class="menu-type-btn">
            <img
              src="https://s.svgbox.net/materialui.svg?ic=delivery_dining&fill=dd0031"
              width="28"
              height="28"
            />
            <strong>Delivery</strong>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
body {
  font-family: "Poppins", sans-serif;
}

h1 {
  color: #004f71;
  font-size: 3rem;
  line-height: 1.2;
  font-weight: 900;
}

.menu-type-btn {
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.25);
  background-color: white;
  border-radius: 20px;
  justify-content: center;
  margin: 16px 12px;
  padding: 1.25rem 2rem;
  font-size: 1.25rem;
  line-height: 1.5;
  display: inline-block;
  text-decoration: none;
  color: #dd0031;
  font-weight: 800;
  word-spacing: 5px;
}
.menu-type-btn img {
  color: #dd0031;
}
.menu-type-btn:hover {
  transform: scale(1.02);
  box-shadow: 0 0 15px rgba(0, 0, 0, 0.35);
  color: #aa0026;
}

</style>