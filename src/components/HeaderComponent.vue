<script setup>

</script>

<template>
  <section class="intro-analytics">
    <div class="wrap wrap-padding">
      <header class="header">
        <a href="#" class="header__logo">
          <img src="@/assets/icons/logo.svg" alt="logo" />
          <p>Analytics</p>
        </a>
        <nav class="header__menu header__menu--adaptive">
          <ul class="header__menu-list">
            <li class="header__menu-item"><a href="#">Products</a></li>
            <li class="header__menu-item"><a href="#">Pricing</a></li>
            <li class="header__menu-item"><a href="#">FAQ</a></li>
            <li class="header__menu-item"><a href="#">Blog</a></li>
            <li class="header__menu-item"><a href="#">Analytics</a></li>
          </ul>
        </nav>
        <div class="header__btns">
          <button class="header__btn--transparent">Sign in</button>
          <button class="header__btn--circled header__menu--adaptive">Sign Up</button>
        </div>

        <div class="header-menu-btn">
          <input type="checkbox" />
          <nav class="header__menu header__menu--side">
            <ul class="header__menu-list">
              <li class="header__menu-item">
                <a href="/" class="header__menu-link">Products</a>
              </li>
              <li class="header__menu-item">
                <a href="/" class="header__menu-link">Pricing</a>
              </li>
              <li class="header__menu-item">
                <a href="/" class="header__menu-link">FAQ</a>
              </li>
              <li class="header__menu-item">
                <a href="/" class="header__menu-link">Blog</a>
              </li>
              <li class="header__menu-item">
                <a href="/" class="header__menu-link">Analytics</a>
              </li>
            </ul>
          </nav>
        </div>
      </header>

      <div class="dashboard">
        <div class="dashboard__info">
          <h1 class="dashboard__title">Monitor your business on real-time dashboard</h1>
          <p class="dashboard__text">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Elementum nisi aliquet volutpat pellentesque
            volutpat est. Sapien in etiam vitae nibh nunc mattis imperdiet sed nullam.
          </p>
          <button class="dashboard__btn">Try for free</button>
        </div>
        <div class="dashboard__pictures">
          <img src="@/assets/img/dashboard-small.png" alt="dashboard picture" />
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>

</style>