<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/IndexMain.vue'
import IndexMain from './components/IndexMain.vue'
import TheDigosSummaryCovid from './components/page-cards/main/TheDigosSummaryCovid.vue'
import TheDigosSummaryVax from './components/page-cards/main/TheDigosSummaryVax.vue'
import TheDigosAlertLevelBoard from './components/page-cards/main/TheDigosAlertLevelBoard.vue'
import TheHealthAndWellbeing from './components/page-cards/main/TheHealthAndWellbeing.vue';
import TheNavigationBar from './components/page-cards/header/TheNavigationBar.vue'
import TheCovidUpdates from './components/page-cards/main/TheCovidUpdates.vue'
</script>

<template>
  <header>
    <TheNavigationBar />
  </header>
  <main>
    <div class="bg-white text-black">
      <TheDigosSummaryCovid />
    </div>
    <div class="bg-white text-black">
      <TheDigosSummaryVax />
    </div>
    <div class="bg-slate-800">
      <TheDigosAlertLevelBoard />
    </div>
    <div class="bg-white text-black">
      <TheHealthAndWellbeing />
    </div>
    <div class="bg-white text-black">
      <TheCovidUpdates />
    </div>
  </main>
  <footer></footer>
</template>

<style>
@import "./assets/base.css";
@import "./index.css";
</style>
