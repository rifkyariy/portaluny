<template>
  <vs-row justify="center">
      <vs-col class="navbar-style" vs-type="flex" vs-justify="center" vs-align="center" w="1"></vs-col>
      <vs-col vs-type="flex" vs-justify="center" vs-align="center" w="10">
        <vs-navbar class="navbar-style" text-dark square center-collapsed v-model="active">
            <template #left>
              <img class="logo" src="@/assets/img/logo.png" alt="">
              
              <h3>Portal Kemahasiswaan</h3>
            </template>
            <template #right>
              <vs-navbar-item :active="active == 'guide'" id="guide">
                Guide
              </vs-navbar-item>
              <vs-navbar-item :active="active == 'docs'" id="docs">
                Documents
              </vs-navbar-item>
              <vs-button id="login"
                gradient
                :active="active == 0"
                @click="active = 0"
              >
                Login SSO
              </vs-button>
            </template>
        </vs-navbar>
      </vs-col>
      <vs-col class="navbar-style" vs-type="flex" vs-justify="center" vs-align="center" w="1"></vs-col>
  </vs-row>
</template>

<script>
  export default {
    data:() => ({
      active: 'guide'
    }),
    mounted() {
      
    }
  }
</script>

<style scoped>
  .navbar-style {
    background-color : #fff;
    height : 80px;
    padding-top : 15px;
    box-shadow:
      0 3.8px 3.2px rgba(0, 0, 0, 0.044)
  }

  .logo {
    width: 50px;
    margin-right: 20px;
  }

  #login {
    margin-left : 20px;
  }
</style>