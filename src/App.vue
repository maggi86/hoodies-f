<template>
<Nav/>
  <router-view/>
</template>

<script>
import Nav from "@/components/navbar.vue"
export default{
  components:{
    Nav
  }
}
</script>
