<template>
  <div>
    <!-- navigasi -->
    <nav class="navbar flex justify-between items-center">
        <!-- logo -->
        <div>
            <img src="" alt="logo elemes.id">
        </div>

        <!-- navigation -->
        <div class="hidden md:block">
            <a href="">Home</a>
            <a href="">About</a>
            <a href="">Promotion <span>HOT</span></a>
            <a href="">Blogs</a>
            <a href="">Contact Us</a>
        </div>

        <!-- button register and login -->
        <div class="flex">
            <button-base :buttonText="'Masuk'" :type="'hidden md:block'"></button-base>
            <button-base :buttonText="'Daftar Sekarang'"></button-base>
        </div>
    </nav>

    <!-- hero -->
    <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
        <!-- Motto / Jargon -->
        <div>
            <p>
                Good Food Us Good Mood
            </p>
        </div>

        <!-- images -->
        <div class="row-span-2">
            <div class="flex justify-center items-center">
                <img src="~/assets/img/hero/Image.png" alt="">
            </div>
        </div>

        <!-- description and CTA -->
        <div>
            <!-- description -->
            <p>
                I would think that conserving our natural resources should be a conservative position: Not to waste food, and not to throw away a lot of the food that we buy.
            </p>

            <!-- CTA -->
            <div class="flex">   
                <button-base :buttonText="'Daftar Sekarang'"></button-base>
                <button-base :buttonText="'About Us'"></button-base>
            </div>
            
        </div>
    </div>



    <!-- navigasi mobile -->
    <div class="fixed md:hidden flex justify-around inset-x-0 bottom-0 py-3 bg-white">
        <div>
            <!-- logo -->
            <a href=""></a>

            <a href="">Home</a>
        </div>
        <div>
            <!-- logo -->
            <a href=""></a>

            <a href="">Promotions</a>
        </div>
        <div>
            <!-- logo -->
            <a href=""></a>

            <a href="">Others</a>
        </div>
    </div>
  </div>
</template>

<script>
import ButtonBase from './elements/ButtonBase.vue'
export default {
  components: { ButtonBase },

}
</script>

<style>

</style>