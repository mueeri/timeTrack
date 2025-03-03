<script setup lang="ts">

</script>

<template>
  <q-layout view="hHh lpR fFf">

    <q-header reveal elevated class="bg-primary text-white" height-hint="98">
      <q-toolbar>
        <q-toolbar-title>
          <q-avatar>
            <img src="https://cdn.quasar.dev/logo-v2/svg/logo-mono-white.svg">
          </q-avatar>
          TimeTrack
        </q-toolbar-title>
      </q-toolbar>

      <q-tabs align="left">
        <q-route-tab to="/history" label="Historie" />
        <q-route-tab to="/tracking" label="Aufzeichnungen" />
        <q-route-tab to="/personalInformation" label="Personendaten" />
      </q-tabs>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>

  </q-layout>
</template>

<style scoped>

</style>