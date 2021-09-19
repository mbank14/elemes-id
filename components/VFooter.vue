<template>
  <div class="flex justify-around   " style="padding:1rem;">
      <!-- logo, description and contact icon -->
    <div class="m-3 footer__sec-1 ">
        <!-- logo elemes -->
        <img src="~/assets/img/logo.png" alt="" class="mb-3">

        <!-- address -->
        <p class="mb-3 text-sm text-gray-500">
            Jl. Prof. DR. Satrio No.7, RT.3/RW.3, Karet Kuningan, 
Kecamatan Setiabudi, Kota Jakarta Selatan, 
Daerah Khusus Ibukota Jakarta 12950
        </p>

        <!-- icon -->
        <div>
            <!-- link email icon -->
            <a href="#">
                <i></i>a
            </a>
            <!-- link contact icon -->
            <a href="#">
                <i></i>a
            </a>
            <!-- link instagram icon -->
            <a href="#"></a>a
        </div>
    </div>

    <!-- categories -->
    <div class="m-3 footer__sec-2 ">
        <!-- title Categories -->
        <h3 class="mb-3 font-semibold">Categories</h3>

        <!-- item categories -->
        <ul class="text-sm text-gray-500">
            <li>
                <a href="">Cupcake</a>
            </li>
            <li>
                <a href="">Pizza</a>
            </li>
            <li>
                <a href="">Kebab</a>
            </li>
            <li>
                <a href="">Salmon</a>
            </li>
            <li>
                <a href="">Dognut</a>
            </li>
        </ul>
    </div>

    <!-- about us -->
    <div class="m-3 footer__sec-3 ">
        <!-- title about us -->
        <h3 class="mb-3 font-semibold">About Us </h3>

        <!-- item about us -->
        <ul class="text-sm text-gray-500">
            <li>
                <a href="">About Us</a>
            </li>
            <li>
                <a href="">FAQ</a>
            </li>
            <li>
                <a href="">Report Problem</a>
            </li>
        </ul>
    </div>

    <!-- newsletter -->
    <div class="m-3 footer__sec-4 ">
        <!-- title newsletter -->
        <h3 class="mb-3 font-semibold   ">
            Newsletter
        </h3>

        <!-- discount -->
        <p class="text-sm text-gray-500 mb-3">
            Get now free 50% discount for alll products on your first order
        </p>
        
        <!-- input email -->
        <div class="flex mb-3">
        <input class="rounded-l-lg border" type="email">
        <button class="p-2 btn--green text-white text-xs rounded-r-lg">SEND</button>
        </div>
        <!-- contact -->
        <div>
            <ul>
                <li class="text-xs">
                    <i></i>  elemesid@gmail.com
                </li>
                <li>
                    <i></i>  0888 1111 2222 
                </li>
            </ul>
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