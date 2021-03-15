<template>
  <div class="projects d-block">
    <b-container>
    <b-row class="justify-content-between text-left" style="padding-top: 9rem;">
      <!-- can be component project-title -->
      <b-col cols="5">
        <p class="sm-ruby-text  pb-1">infos zur projekt</p>
        <h3 class="text-left">ZWEI FLINKE<br />BOXER JAGEN DIE</h3>
      </b-col>
      <!-- can be component project-description -->
      <b-col cols="5">
        <p class="text-justify">
          Zwei flinke Boxer jagen die quirlige Eva und ihren Mops durch Sylt.
          Franz jagt im komplett verwahrlosten Taxi quer durch Bayern. Zwölf
          Boxkämpfer jagen Viktor quer über den großen Sylter Deich. Vogel Quax
          zwickt
        </p>
        <p class="text-left">
          <a href="#">LEARN MORE</a>
        </p>
      </b-col>
    </b-row>

    <b-row class="py-5 justify-conte-between" >
      <b-col cols="4">
        <Card1of3
          urlImg="https://picsum.photos/id/242/600"
          head="Project Title Here"
          text="Zwei flinke Boxer jagen die quirlige Eva und ihren Mops durch Sylt. Franz jagt"
        />
      </b-col>
      <b-col cols="4">
        <Card1of3
          urlImg="https://picsum.photos/id/243/600"
          head="Project Title Here"
          text="Zwei flinke Boxer jagen die quirlige Eva und ihren Mops durch Sylt. Franz jagt"
        />
      </b-col>
      <b-col cols="4">
        <Card1of3
          urlImg="https://picsum.photos/id/244/600"
          head="Project Title Here"
          text="Zwei flinke Boxer jagen die quirlige Eva und ihren Mops durch Sylt. Franz jagt"
        />
      </b-col>
    </b-row>
    </b-container>
  </div>
</template>

<style scoped>
.projects {
 background-color: rgba(252, 245, 207, 1);;
}
</style>