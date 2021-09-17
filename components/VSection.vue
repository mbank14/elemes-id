<template>
  <section>
      <!-- Title -->
      <div class="my-2">
          <p>{{ mainTitle }}</p>
          <p>{{ secondTitle }}</p>
      </div>

      <!-- show menus -->
      <div class="my-2">
          <slot name="mainMenus"></slot>
      </div>
  </section>
</template>

<script>
export default {
    name: 'VSection',
    props: {
        mainTitle: {
            require: true,
            type: String,
            default: 'Browser Our Menus'
        },
        secondTitle: {
            type:String,
            default: 'Receipt'
        }
    }
}
</script>

<style>

</style>