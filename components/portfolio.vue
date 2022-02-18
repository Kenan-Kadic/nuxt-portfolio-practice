<template>
  <v-container>
    <div id="component-profile" class="d-flex flex-column justify-center align-center">
      <img src="~assets/img/man.jpeg"/>
      <h1> {{ name }}</h1>
      <p> {{ description }}</p>
      <div class="d-flex">
        <v-icon class="icon mx-2">mdi-github</v-icon>
        <v-icon class="icon mx-2">mdi-linkedin</v-icon>
        <v-icon class="icon mx-2">mdi-facebook</v-icon>
      </div>
    </div>
  </v-container>
</template>

<script>
export default {

  data() {
    return {
      name: 'John Henry',
      description: 'I am a Frontend developer from America'
    }
  }
}
</script>

<style scoped lang="scss">
  #component-profile {
    height: 100vh;

  img {
    max-height: 100px;
    border-radius: 100px;
  }

  .icon{
    font-size: 44px;
    color: yellowgreen;
  }
}


</style>
