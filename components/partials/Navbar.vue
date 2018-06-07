<template>
  <!-- Main sidebar menu -->
    <nav class="main-menu">
        <div class="main-menu-inner">
          <!-- Side icon menu -->
          <ul>
            <li class="main-logo">
                <a href="dashboard.html">
                  <img src="~/assets/images/logos/square-violet.svg" alt="">
                </a>
            </li>
            <li class="side-icon is-active" data-child-menu="dashboard-menu">
                <i class="sl sl-icon-speedometer"></i>
            </li>
            <li class="side-icon" data-child-menu="documents-menu">
                <i class="sl sl-icon-docs"></i>
            </li>
            <li class="side-icon" data-child-menu="business-menu">
                <i class="sl sl-icon-briefcase"></i>
            </li>
            <li class="side-icon" data-child-menu="misc-menu">
                <i class="sl sl-icon-graph"></i>
            </li>
            <li class="side-icon" data-child-menu="settings-menu">
                <i class="sl sl-icon-settings"></i>
            </li>
          </ul>
          <!-- /Side icon menu -->

          <!-- Profile wrapper -->
          <!-- Profile wrapper -->
          <ul class="profile">
            <li>
              <!-- Profile avatar -->
              <a class="profile-trigger" href="javascript:void(0);">
                  <img class="main-menu-avatar" src="https://place-hold.it/250x250" alt="">
                  <span class="dot"></span>
              </a>
              <!-- /Profile avatar -->
            </li>
          </ul>
        </div>
    </nav>
    <!-- /Main sidebar menu -->
</template>

<script>
export default {}
</script>