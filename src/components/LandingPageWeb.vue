<template>

  <div class="page-body">

    <section class="first-section">
      <div class="navbar-list">
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Services</a></li>
          <li><a href="#">FAQs</a></li>
        </ul>

        <button>Log In</button>
      </div>
    </section>

    <section class="second-section">
      My name is okoroafor Kelechi
    </section>
  </div>



</template>

<script>

import LandingPageCss from "@/components/LandingPage.css"
export default {
  name: "LandingPageWeb",
  components:{
    // eslint-disable-next-line vue/no-unused-components
    LandingPageCss
  },
}

</script>
<style scoped>
</style>