<!-- <template>
  <nav>
    <router-link to="/">ບ້ານ</router-link> |
    <router-link to="/about">ກ່ຽວກັບ</router-link>
  </nav>
  <router-view/>
</template> -->

<template>
  <!-- MENU -->
  <MenuComponent/>

  <router-view/>

  <!-- FOOTER -->
  <FooterComponent/>
</template>

<script>
  import MenuComponent from '@/components/MenuComponent.vue'
  import FooterComponent from '@/components/FooterComponent.vue'

  export default{
    components: {
        MenuComponent,
        FooterComponent
    }
}
</script>