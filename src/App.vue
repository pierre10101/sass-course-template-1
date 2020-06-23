<template>
  <div id="app">
    <div id="nav">
      <div class="navigation">
        <input id="nav-toggle" type="checkbox" class="navigation__checkbox" />
        <label for="nav-toggle" class="navigation__button">
          <span class="navigation__icon">&nbsp;</span>
        </label>
        <div class="navigation__background">&nbsp;</div>
        <nav class="navigation__nav">
          <ul class="navigation__list">
            <li class="navigation__item">
              <router-link to="/" class="navigation__link">About Natous</router-link>
            </li>
            <li class="navigation__item">
              <router-link to="/about" class="navigation__link">Your benefits</router-link>
            </li>
            <li class="navigation__item">
              <router-link to="/about" class="navigation__link">Popular Tours</router-link>
            </li>
            <li class="navigation__item">
              <router-link to="/about" class="navigation__link">Stories</router-link>
            </li>
            <li class="navigation__item">
              <router-link to="/about" class="navigation__link">Book now</router-link>
            </li>
          </ul>
        </nav>
      </div>
    </div>
    <router-view />
  </div>
</template>
