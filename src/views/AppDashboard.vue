<script setup>
import CustomerDashboard from "./Customer/CustomerDashboard.vue";
import AdminDashboard from "./Admin/AdminDashboard.vue";
import { RouterView } from "vue-router";
const isCustomer = true;
</script>
<template>
  <div>
    <CustomerDashboard v-if="isCustomer">
      <RouterView />
    </CustomerDashboard>
    <AdminDashboard v-else>
      <RouterView />
    </AdminDashboard>
  </div>
</template>
