<template>
    <nav class="site-header sticky-top py-1">
      <div class="container d-flex flex-column flex-md-row justify-content-between">
        <a class="py-2" href="#" aria-label="Product">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            fill="none"
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            class="d-block mx-auto"
            role="img"
            viewBox="0 0 24 24"
            focusable="false"
          >
            <circle cx="12" cy="12" r="10" />
            <path
              d="M14.31 8l5.74 9.94M9.69 8h11.48M7.38 12l5.74-9.94M9.69 16L3.95 6.06M14.31 16H2.83m13.79-4l-5.74 9.94"
            />
          </svg>
        </a>
        <a class="py-2 d-none d-md-inline-block" href="#">Menu</a>
        <a class="py-2 d-none d-md-inline-block" href="#">Order</a>
        <a class="py-2 d-none d-md-inline-block" href="#">About</a>
        <a class="py-2 d-none d-md-inline-block" href="#">Restaurants</a>
        <a class="py-2 d-none d-md-inline-block" href="#">Offers</a>
      </div>
    </nav>

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