<template>
  <div class="about">
    <!-- {{ their_name }} faire apparaitre le nom de la personne ou autre, tapper apres about/... -->
    <h1>This is an about page</h1>
    <p> tesdssssssddddddddddddddddqjjzhdhzah  hz dbhazdzdhajhdahzdbzbhdah hb dzj bdhazdbzadhazbdhjzbabjdazd</p>
  </div>
</template>


<script>
export default {
  data() {
    return{
      their_name: this.$route.params.name
    }
  }
}
</script>
