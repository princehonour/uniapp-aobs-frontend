<template>
  <div>
    <header class="navbar navbar-expand-md navbar-dark bd-navbar">
      <nav
        class="container-xxl flex-wrap flex-md-nowrap"
        aria-label="Main navigation"
      >
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#bdNavbar"
          aria-controls="bdNavbar"
          aria-expanded="false"
          aria-label="Toggle navigation"
        ></button>

        <div class="collapse navbar-collapse" id="bdNavbar">
          <ul class="navbar-nav flex-row flex-wrap bd-navbar-nav pt-2 py-md-0">
            <li class="nav-item col-6 col-md-auto">
              <a class="nav-link p-2" href="/">首页</a>
            </li>
            <li class="nav-item col-6 col-md-auto">
              <a
                class="nav-link p-2"
                href="/docs/examples/"
                onclick="ga('send', 'event', 'Navbar', 'Community links', 'Examples');"
                >示例</a
              >
            </li>
          </ul>
        </div>
      </nav>
    </header>
  </div>
</template>