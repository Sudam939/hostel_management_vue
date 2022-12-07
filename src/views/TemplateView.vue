<template>
  <div>
    <!-- Navbar -->
    <header>
        <navbar-comp/>
    </header>
    
    <main>
       <slot> </slot>
    </main>

    <!-- Footer -->
    <footer>
      <footer-comp/>
    </footer>
  </div>
</template>

<script>
import FooterComp from '@/components/FooterComp.vue'
import NavbarComp from '@/components/NavbarComp.vue'
export default {
name:"TemplateView",
components:{NavbarComp, FooterComp}
}
</script>

<style>

</style>