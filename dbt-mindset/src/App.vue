<template>
  <div id="app">
    <h1>DBT Mindset</h1>
    <div class="content">
      <a class="twitter-timeline" data-width="800" data-height="550" data-theme="dark" data-link-color="#2B7BB9" href="https://twitter.com/dbtmindset?ref_src=twsrc%5Etfw">Tweets by dbtmindset</a>
    </div>
    <div class="items">
      <ul>
        <li><a href="/flashcards/">DBT Flashcards</a></li>
      </ul>
    </div>
  </div>
</template>

<script>

</script>

<style>

body, html {
  height: 100%;
  margin: 0;
  padding: 0;
}
#app {
  margin: 0px;
  padding: 25px;
  height: 100%;
  color: white;

  /* Center and scale the image nicely */
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  background-image: url("https://github.com/dbtmindset/dbtmindset.github.io/raw/master/src/assets/fog-rock-stand.jpg");
}
.content {
  margin-left:100px;
}
a:link {
  color: white;
}
a:visited {
  color: gray;
}
a:hover {
  color: gray;
}
a:active {
  color: white;
}

</style>
