<template>
  <template-view>
    <div class="title d-flex justify-content-center">
      <h2>Admission</h2>
    </div>
    <div class="container">
      <card-comp/>
      <card-comp/>
      <card-comp/>
      <card-comp/>
      
    </div>
  </template-view>
</template>

<script>
import CardComp from '@/components/CardComp.vue'
import TemplateView from './TemplateView.vue'
export default {
name:'AdmissionView',
components:{TemplateView, CardComp}
}
</script>

<style>

</style>