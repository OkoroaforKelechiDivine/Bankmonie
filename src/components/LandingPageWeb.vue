<template>
  <body>
  <header>
    <img class="logo" src="../assets/ankmonie.png" alt="logo not found"/>
    <nav>
      <ul class="nav_links">
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">FAQs</a></li>
      </ul>
    </nav>
    <a class="cta" ref="#"><button>Contacts</button></a>
  </header>
  </body>
<!--  <section>-->

<!--  </section>-->
</template>

<script>

import LandingPageCss from "@/components/LandingPage.css"
// import Index from "../../public/index.html";
export default {
  name: "LandingPageWeb",
  components:{
    // Index,
    // eslint-disable-next-line vue/no-unused-components
    LandingPageCss
  },
}

</script>
<style scoped>
</style>