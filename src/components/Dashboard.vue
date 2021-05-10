<template>
  <DashCards/>
</template>

<script>
import DashCards from "@/components/DashCards";
export default {
  name:'Dashboard',
  components: {DashCards},
  props:{
    title:String
  }
}
</script>