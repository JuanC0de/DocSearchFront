<script>
import FormLogin from '../../layouts/FormLogin/FormLogin.vue'
import MenuComponent from '@/components/Menu.vue'

export default {
  name: "LoginForm",
  /********* Componentes  ********/
  components: {
    FormLogin,
    MenuComponent,
  },
};
</script>

<template>
    <div class="my-view">
      <MenuComponent/>
      <FormLogin/>
    </div>
</template>

<style>
    .my-view {
        background-image: url('@/assets/images/pacienteMedico.png');
        background-size: cover;
        background-position: relative;
        min-height: 100vh;
        margin: 30px;
    }
</style>
