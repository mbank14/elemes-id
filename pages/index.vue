<template>
  <!-- <Tutorial/> -->
  <div class="container mx-auto px-7">
    <!-- header content -->
    <header>
      <v-header></v-header>
    </header>
    
    <!-- main content -->
    <main>
      <!-- Category -->
      <v-section></v-section>

      <!-- trending -->
      <v-section></v-section>
    </main>


    <footer class="hidden md:block footer rounded-lg">
      <v-footer></v-footer>
    </footer>


    <!-- <button-base :buttonText="'daftar sekarang'"></button-base>
    <div style="width:300px;">
      <card-base></card-base>
    </div> -->


  </div>
  
</template>

<script>
import CardBase from '~/components/elements/CardBase.vue'
import ButtonBase from '~/components/elements/ButtonBase.vue'
import VHeader from '~/components/VHeader.vue'
import VSection from '~/components/VSection.vue'
import VFooter from '~/components/VFooter.vue'
export default {
  components: { ButtonBase, CardBase, VHeader, VSection, VFooter },
  }
</script>
