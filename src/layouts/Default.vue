<template>
  <div class="layout">
    <slot/>
    <div class="footer">
      <p>
        Built with
        <a class="link" href="//gridsome.org">Gridsome</a>
        & Made by
        <a class="link" href="//github.com/evadi/">evadi</a>
      </p>
    </div>
  </div>
</template>

<style>
body {
  font-family: -apple-system, system-ui, BlinkMacSystemFont, "Segoe UI", Roboto,
    "Helvetica Neue", Arial, sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.5;
  border: 15px solid #4384fe;
  min-height: 100vh;
}
.layout {
  max-width: 760px;
  margin: 0 auto;
  padding-left: 20px;
  padding-right: 20px;
}
.footer {
  padding-top: calc(30em / 4);
  text-align: center;
  font-size: 1em;
}
.link {
  border: 2px dashed #4384fe;
  padding: 7px;
  color: #333;
  text-decoration: none;
}
</style>