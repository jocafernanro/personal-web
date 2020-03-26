<template>
  <div id="app">
    <home-header></home-header>
    <home-main></home-main>
  </div>
</template>

<script>

import HomeHeader from './components/home/HomeHeader'
import HomeMain from './components/home/HomeMain'

export default {
  name: 'App',
  components: {
    HomeMain,
    HomeHeader
  }
}
</script>

<style>
  :root {
    --blue-darkest: #131C25;
    --blue-light: #169CFC;
    --white: #E3E4E5;
    --grey-light: #919191;
    --black: #1B1B1B;
    --yellow: #E3B044;

    --weight-bolder: 700;
    --weight-normal: 500;

    --text-title-size: 7em;
    --text-title-max-width: 40em;
    --text-subtitle-size: 2.8em;
    --text-subtitle-line-height: 1em;
    --text-text-size: 1.8em;
    --text-location-size: 1em;

    --menu-item-display: inline;

    --home-header-nav-width: 80vw;
    --home-header-nav-margin: 0 auto;
    --home-header-menu-padding: 3em 0;
    --main-mobile-margin: 1em;
  }

  @media screen and (max-width: 750px) {
    :root {
      --text-title-size: 4em;
      --text-title-max-width: 7em;
      --text-subtitle-size: 2.2em;
      --text-subtitle-line-height: 1.2em;
      --text-text-size: 1.5em;
      --text-location-size: 1.2em;

      --menu-item-display: block;

      --home-header-nav-width: 100vw;
      --home-header-nav-margin: 0 auto;
      --home-header-menu-padding: 1.5em 1em;
      --main-mobile-margin: 1em;
    }
  }

  @media screen and (max-width: 375px) {
    :root {
      --text-title-size: 3em;
      --text-title-max-width: 4em;
      --text-subtitle-size: 1.8em;
      --text-subtitle-line-height: 1.2em;
    }
  }

  html {
    font-size: 100%;
  }

  *{
    padding: 0;
    margin: 0;
  }

  body {
    font-family: neue-haas-grotesk-display, sans-serif;
    font-weight: 400;
    background-color: var(--black);
    color: white;
  }
</style>

<style lang="scss" scoped>
  #app {
  margin: 0;
  }
</style>
