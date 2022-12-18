<template>
  <div class="container-fluid">
    <div id="first-page" class="full-height m-0 p-0">
      <h1>This Website is currently being developed...</h1>

    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

export default class Home extends Vue {}
</script>

<style lang="scss">
  $darkest-blue : #1A1A2E;
  $dark-blue : #16213E;

  #first-page {
    background-color: $dark-blue;
    background: url('https://ik.imagekit.io/ekjfugtun/haseeb-portfolio/MyWebsitebg_JEuOkXlTx.png?ik-sdk-version=javascript-1.4.3&updatedAt=1660087982167') no-repeat center center;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;

    position: sticky;
  }
  .bg-dark-blue{
    background-color: $dark-blue;
  }
  .bg-darkest-blue{
    background-color: $darkest-blue;
  }
  
</style>