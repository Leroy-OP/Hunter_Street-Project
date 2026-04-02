<script setup>
import Navbar from "./components/navbar.vue"
</script>

<template>
    <v-app>
      <Navbar/>
      <v-main>
        <transition name="fade" mode="out-in">
          <router-view />
        </transition>
      </v-main>
    </v-app>
</template>
