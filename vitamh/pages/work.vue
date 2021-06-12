<template>
  <div class="container">
    <div class="row nav subtitle">
        <NLink to="/">
          Home
        </NLink>
        <NLink to="/work" class="active">
          Work
        </NLink>
        <NLink to="/contact">
          Contact
        </NLink>
    </div>
    <div class="row content">
      <iframe height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/1062973279&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe></br>
      <iframe height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/1062974647&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe></br>
      <iframe height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/1062975793&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.container {
  min-height: 100vh;
  height: 100%;
  width: 100%;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  vertical-align: top;
}

.nav {
  padding: 10px;
  clear: both;
  width: 100%;
}

a {
  text-decoration: none;
  color: grey;
}

a:hover {
  color: white;
}

.active {
  font-weight: 900;
}

.content {
 /* width: 100%;
  height: 0.5;*/
  text-align: center;
  clear: both;
  padding: 10px;
  justify-content: center;
  align-items: center;
  width: 100%;
}

.title {
  font-family:
    Arial,
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: white;
  letter-spacing: 1px;
}

.subtitle {
  font-family:
    Arial,
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    sans-serif;
  font-weight: 300;
  font-size: 42px;
  color: grey;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.container {
  background-color: black;
}

.links {
  padding-top: 15px;
}

.active {
  color: grey;
}

</style>
