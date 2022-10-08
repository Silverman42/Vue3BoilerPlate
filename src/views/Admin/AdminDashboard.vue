<script setup>
import { RouterLink } from "vue-router";
import NavBar from "../../components/NavBar.vue";
</script>
<template>
  <div class="flex items-stretch">
    <nav class="sidebar">
      <RouterLink class="sidebar-logo" to="/">Custom</RouterLink>
      <ul class="sidebar-container">
        <li class="sidebar-link--header">Dashboard</li>
        <li class="sidebar-link">
          <RouterLink to="/"
            ><span class="sidebar-link-icon">
              <i data-feather="grid" width="18"></i>
            </span>
            <span>View dashboard</span></RouterLink
          >
        </li>
      </ul>
      <ul class="sidebar-container">
        <li class="sidebar-link--header">Links</li>
        <li class="sidebar-link">
          <RouterLink to="/"
            ><span class="sidebar-link-icon">
              <i data-feather="list" width="18"></i>
            </span>
            <span>View links</span></RouterLink
          >
        </li>
        <li class="sidebar-link">
          <RouterLink to="/"
            ><span class="sidebar-link-icon">
              <i data-feather="list" width="18"></i>
            </span>
            <span>View links</span></RouterLink
          >
        </li>
        <li class="sidebar-link">
          <RouterLink to="/"
            ><span class="sidebar-link-icon">
              <i data-feather="list" width="18"></i>
            </span>
            <span>View links</span></RouterLink
          >
        </li>
      </ul>
      <ul class="sidebar-container">
        <li class="sidebar-link--header">Payment</li>
        <li class="sidebar-link">
          <RouterLink to="/"
            ><span class="sidebar-link-icon">
              <i data-feather="list" width="18"></i>
            </span>
            <span>View links</span></RouterLink
          >
        </li>
        <li class="sidebar-link">
          <RouterLink to="/"
            ><span class="sidebar-link-icon">
              <i data-feather="list" width="18"></i>
            </span>
            <span>View links</span></RouterLink
          >
        </li>
      </ul>
      <ul class="sidebar-container">
        <li class="sidebar-link--header">Settings</li>

        <li class="sidebar-link">
          <RouterLink to="/"
            ><span class="sidebar-link-icon">
              <i data-feather="list" width="18"></i>
            </span>
            <span>View links</span></RouterLink
          >
        </li>
        <li class="sidebar-link">
          <RouterLink to="/"
            ><span class="sidebar-link-icon">
              <i data-feather="list" width="18"></i>
            </span>
            <span>View links</span></RouterLink
          >
        </li>
      </ul>
    </nav>
    <section class="main">
      <div
        class="absolute z-0 top-0 left-0 w-full h-80 bg-gradient-to-b from-yellow-50 to-white shadow-inner shadow-white"
      ></div>
      <NavBar></NavBar>
      <main class="p-6 z-10 relative">
        <div class="max-w-6xl mx-auto">
          <slot />
        </div>
      </main>
    </section>
  </div>
</template>
<style></style>
