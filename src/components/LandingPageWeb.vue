<template>

  <div class="page-body">
    <section class="first-section">
      <nav>
        <input type="checkbox" id="check">
        <label for="check" class="checkbtn">
          <i class="fas fa-bars"></i>
        </label>
        <label class="logo">Bankmonie</label>
          <ul>
            <li><a class="active" href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">FAQs</a></li>
            <li><a href="#">Log In</a> </li>
          </ul>
      </nav>
    </section>

<!--    <section class="second-section">-->
<!--      My name is okoroafor Kelechi-->
<!--    </section>-->
  </div>



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