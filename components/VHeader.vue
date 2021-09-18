<template>
  <div>
    <!-- navigasi -->
    <nav>
        <!-- logo -->
        <div>
            <img src="" alt="logo elemes.id">
        </div>

        <!-- navigation -->
        <div>
            <a href="">Home</a>
            <a href="">About</a>
            <a href="">Promotion <span>HOT</span></a>
            <a href="">Blogs</a>
            <a href="">Contact Us</a>
        </div>

        <!-- button register and login -->
        <div>
            <button-base :buttonText="'Daftar Sekarang'"></button-base>
        </div>
    </nav>

    <!-- hero -->
    <div>
        <!-- Motto / Jargon -->
        <div>
            <p>
                Good Food Us Good Mood
            </p>
        </div>

        <!-- images -->
        <div></div>

        <!-- description and CTA -->
        <div>
            <!-- description -->
            <p>
                I would think that conserving our natural resources should be a conservative position: Not to waste food, and not to throw away a lot of the food that we buy.
            </p>

            <!-- CTA -->
            <div>   
                <button-base :buttonText="'Daftar Sekarang'"></button-base>
                <button-base :buttonText="'About Us'"></button-base>
            </div>
            
        </div>
    </div>



    <!-- navigasi mobile -->
    <div>
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