<template>
  <div>
    <vs-navbar text-dark square center-collapsed v-model="active">
      <template #left>
        <img src="/logos/logo-vuesax-logotipo-vuesax-png-4.png" alt="">
      </template>
      <vs-navbar-item :active="active == 'guide'" id="guide">
        Guide
      </vs-navbar-item>
      <vs-navbar-item :active="active == 'docs'" id="docs">
        Documents
      </vs-navbar-item>
      <vs-navbar-item :active="active == 'components'" id="components">
        Components
      </vs-navbar-item>
      <vs-navbar-item :active="active == 'license'" id="license">
        license
      </vs-navbar-item>
      <template #right>
        <vs-button color="#fff" flat >Login</vs-button>
        <vs-button color="#fff" border >Get Started</vs-button>
      </template>
    </vs-navbar>
    <vs-card>
    <template #title>
      <h3>Pot with a plant</h3>
    </template>
    <template #img>
      <img src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg" alt="">
    </template>
    <template #text>
      <p>
        Lorem ipsum dolor sit amet consectetur, adipisicing elit.
      </p>
    </template>
    <template #interactions>
      <vs-button danger icon>
        <i class='bx bx-heart'></i>
      </vs-button>
      <vs-button class="btn-chat" shadow primary>
        <i class='bx bx-chat' ></i>
        <span class="span">
          54
        </span>
      </vs-button>
    </template>
  </vs-card>
  </div>
</template>

<script>
import Vue from 'vue'
import Vuesax from 'vuesax'
import Navbar from '~/components/Navbar.vue'


export default {
}
</script>

<style>
</style>
