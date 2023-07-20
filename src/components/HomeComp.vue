<template>
   <teleport to="#footer">
    <FooterComp />
   </teleport>
</template>
<script>
import FooterComp from './FooterComp.vue'

export default {
    name:"HomeComp",
    components:{
        FooterComp

    }
}
</script>
<style scoped>

</style>