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
      <v-section :mainTitle="'Browser Our Trending'" class="section__trending">
        <template v-slot:mainMenus>
          <div class="grid grid-cols-1 md:grid-cols-4 gap-4 mb-16">
            <card-base>
              <div>
                
                  <img  class="section__trending-img"
                  src="~/assets/img/trending/pexels-alena-shekhovtcova-6940978 1.png" alt="">
               
                <div>
                  <p>Doughnut Milk</p>
                  <p>Doughnut</p>
                  <i>bintang</i>
                </div>
              </div>
            </card-base>
            
            <card-base>
              <div>
                <div>foto</div>
                <div>
                  <p>pizza</p>
                  <p>category</p>
                  <i>bintang</i>
                </div>
              </div>
            </card-base>
            <card-base>
              <div>
                <div>foto</div>
                <div>
                  <p>pizza</p>
                  <p>category</p>
                  <i>bintang</i>
                </div>
              </div>
            </card-base>
            <card-base>
              <div>
                <div>foto</div>
                <div>
                  <p>pizza</p>
                  <p>category</p>
                  <i>bintang</i>
                </div>
              </div>
            </card-base>

          </div>

          <div class="md:flex justify-center hidden">
            <button-base :buttonText="'All Receipt'"></button-base>
          </div>
        </template>
      </v-section>
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
