<template>
  <v-container>

    <!--Seller Navigation Drawer-->
    <seller-navi/>

    <!--Top bar-->
    <v-app-bar color="white" elevate-on-scroll height="80" app elevation="3">
      <v-toolbar-title class="ml-3" style="color: #2F4F4F">
        📌 Order Manage
      </v-toolbar-title>
    </v-app-bar>

  </v-container>
</template>

<script>
import SellerNavi from "@/components/seller/SellerNavi";
export default {
  name: "OrderManageForm",
  components: {SellerNavi}
}
</script>

<style scoped>

</style>