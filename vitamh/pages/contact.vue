<template>
  <div class="container">
    <div class="row nav subtitle">
        <NLink to="/">
          Home
        </NLink>
        <NLink to="/work">
          Work
        </NLink>
        <NLink to="/contact" class="active">
          Contact
        </NLink>
    </div>
    <div class="row content">
      <h2 class="subtitle">
        vita.measurehughes@gmail.com
      </h2>
      <h2 class="subtitle">
        soundcloud.com/vitamh
      </h2>
      <h2 class="subtitle">
        instagram.com/vitamh_art
      </h2>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.container {
  min-height: 100vh;
}

.nav {
  padding: 10px;
 /* display: flex;
  flex-direction: row;
  flex-wrap: wrap;*/
/*  vertical-align: top;
  height: 0.5;*/
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

.row {
  width: 100%;
  min-height: 20vh;
}

.content {
 /* width: 100%;
  height: 0.5;*/
  /*display: flex;
  flex-direction: row;
  flex-wrap: wrap;*/
  margin-top: -100px;
  text-align: center;
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
