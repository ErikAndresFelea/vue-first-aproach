<script setup>
import TheWelcome from '../components/TheWelcome.vue'
import HelloWorld from '../components/HelloWorld.vue'
import WelcomeItem from '../components/WelcomeItem.vue'
</script>

<template>
  <main>
    <HelloWorld />
    <h3>So many components...</h3>
    <TheWelcome />
    <h3>Actualy too many...</h3>
    <WelcomeItem />
    <WelcomeItem />
    <WelcomeItem />
    <WelcomeItem />
    <WelcomeItem />
    <h3>Please stop</h3>
    <HelloWorld />
    <TheWelcome />
  </main>
</template>