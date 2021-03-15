<template>
  <b-navbar type="dark" class="py-5" >
      <b-navbar-nav class="mx-auto">
        <b-nav-item-dropdown class="mx-3"  text="Mitwirkende" right>
          <b-dropdown-item href="#">Hauptdarsteller</b-dropdown-item>
          <b-dropdown-item href="#">Buhnenpersonal</b-dropdown-item>
          <b-dropdown-item href="#">Unterstutzer</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item class="mx-3" to="/aufreisen">Auf Reisen</b-nav-item>
        <b-nav-item class="mx-3" to="/kalender">Kalender</b-nav-item>
        <b-nav-item class="mx-3" to="/aufnahmen">Aufnahmen</b-nav-item>
        <b-nav-item class="mx-3" to="/stimmen">Stimmen</b-nav-item>
        <b-nav-item class="mx-3" to="/aktuel">Aktuell</b-nav-item>
        <b-nav-item class="mx-3" to="/kontakt">Kontakt</b-nav-item>
        <b-nav-item class="mx-3" href="#">EN</b-nav-item>
      </b-navbar-nav>
      </b-navbar>
</template>

<style scoped>
.navbar {
  background-color: transparent;
  position: absolute;
  width: 100%;
}
</style>