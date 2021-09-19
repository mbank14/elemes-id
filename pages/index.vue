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
      <v-section :mainTitle="'Browser Our Categpry'" class="section__category">
        <template v-slot:mainMenus>
          <div>

          </div>
        </template>
      </v-section>

      <!-- trending -->
      <v-section :mainTitle="'Browser Our Trending'" class="section__trending">
        <template v-slot:mainMenus>
          <div class="grid grid-cols-1 md:grid-cols-4 gap-4 mb-16">
            <card-base>
              <div>
                
                  <img  class="section__trending-img"
                  src="~/assets/img/trending/pexels-alena-shekhovtcova-6940978 1.png" alt="">
               
                <div>
                  <p class="font-semibold text-lg">Doughnut Milk</p>
                  <p class="txt--green text-sm">Doughnut</p>
                  <i>bintang</i>
                </div>
              </div>
            </card-base>
            
            

          </div>

          <div class="md:flex justify-center hidden">
            <button-base :buttonText="'All Receipt'" :type="'btn--green text-white'"></button-base>
          </div>
        </template>
      </v-section>
    </main>


    <footer class="hidden md:block footer rounded-lg">
      <v-footer></v-footer>
    </footer>
      <div class="mx-auto py-4">
        <center>
        <h1 class="text-sm">2021</h1>
        </center>
      </div>


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
  data() {
    return{
      currentIndex: 0,
      indexSlide : 0,
      itemCat: [
        {
          id: 1,
          name: 'Cupcake',
          qty: 22,
          img: '~/assets/img/category/Frame.svg'
        },
        {
          id: 2,
          name: 'Pizza',
          qty: 25,
          img: '~/assets/img/category/pizza 1.svg'
        },
        {
          id: 3,
          name: 'Kebab',
          qty: 12,
          img: '~/assets/img/category/kebab 1.svg'
        },
        {
          id: 4,
          name: 'Salmon',
          qty: 22,
          img: '~/assets/img/category/salmon 1.svg'
        },
        {
          id: 5,
          name: 'Doughnut',
          qty: 1,
          img: '~/assets/img/category/doughnut 1.svg'
        },
      ],

    }
  },

  methods:{
    
  }
  }
</script>
