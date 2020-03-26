<template>
  <header class="home-header">
    <nav class="home-header__nav">
      <ul class="home-header__menu">
        <li class="home-header__item"><a class="home-header__link" href="https://github.com/jocafernanro"><i class="fab fa-github-alt"></i>Github</a></li>
        <li class="home-header__item"><a class="home-header__link" href="https://codepen.io/jocafernanro"><i class="fab fa-codepen"></i>Codepen</a></li>
        <li class="home-header__item"><a class="home-header__link" href="https://dev.to/jocafernanro"><i class="fab fa-dev"></i>Dev.to</a></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'home-header'
}
</script>

<style lang="scss" scoped>
  .home-header{

    &__nav{
      color: white;
      height: 100px;
      width: var(--home-header-nav-width);
      max-width: 56.26em;
      margin: var(--home-header-nav-margin);
      text-align: right;
    }

    &__menu{
      list-style-type: none;
      margin: 0;
      padding: var(--home-header-menu-padding);
    }

    &__item{
      display: var(--menu-item-display);
      font-size: 1.3em;
      padding: 0.3em 0.7em;
    }

    &__link{
      text-align: center;
      text-decoration: none;
      color: white;
        .fab{
          margin: 0 0.5em 0 0;
        }
    }
  }
</style>
