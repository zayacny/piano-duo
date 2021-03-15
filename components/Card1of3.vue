<template>
    <b-card
    :title="head"
    :img-src="urlImg"
    img-alt="Image"
    img-top
    tag="article"
    style="border:0; height"
    class="text-left d-flex flex-column"
    no-body
  >
    <b-card-text class="py-3" style="height: 8rem; overflow: hidden; text-overflow:clip; ">
      <h4>{{head}}</h4>
     {{text}}
    </b-card-text>
    <b-button v-if="link" href="#" variant="link" class="text-left pl-0">Read more</b-button>
  </b-card>
</template>

<script>
export default {
 props: {
   urlImg: String,
   head: String,
   text: String,
   link: Boolean
 }
}
</script>

<style scoped>
.card{
 background-color: inherit;
}
</style>