<template>
  <footer>
    <div class="container">
      <div class="row">
        <div class="col text-center">
         <SiteLogo />
        </div>
        <div class="col">
          <h3>Pastificio</h3>
          <ul>
            <li>Il Pastificio</li>
            <li>Grano</li>
            <li>Filiera</li>
            <li>100 anni di pasta</li>
            <li>Storai della pasta</li>
          </ul>
        </div>
        <div class="col">
          <h3>Pastificio</h3>
          <ul>
            <li>Il Pastificio</li>
            <li>Grano</li>
            <li>Filiera</li>
            <li>100 anni di pasta</li>
            <li>Storai della pasta</li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
import SiteLogo from '@/components/LogoComponent.vue'
export default {
  name: "FooterComponent",
  components :{
      SiteLogo
  }
};
</script>

<style lang="scss" scoped>
footer {
  background-image: url("@/assets/img/footer-montagne-bottom.jpg");
  background-repeat: no-repeat;
  background-position: bottom;
  height: 400px;
  padding-top: 3rem;
  h3 {
      margin-bottom: 1.25rem;
  }
  ul {
    list-style: none;
    line-height: 1.5rem;
  }
}
</style>