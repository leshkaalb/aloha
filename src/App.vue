<template>
    <div id="app">
        <Header />
        <Main />
    </div>
</template>

<script setup>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
</script>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
}
</style>