<template>
  <div class="container">
    <div class="row nav subtitle">
        <NLink to="/" class="active">
          Home
        </NLink>
        <NLink to="/work">
          Work
        </NLink>
        <NLink to="/contact">
          Contact
        </NLink>
    </div>
    <div class="row content">
      <h1 class="title">
        vita mh
      </h1>
      <h2 class="subtitle">
        website coming soon
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
  min-width: 100vh;
}

.nav {
  padding: 10px;
  width: 100%;
  min-width: 100vh;
  min-height: 20vh;
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
}

.content {
 /* width: 100%;
  height: 0.5;*/
  /*display: flex;
  flex-direction: row;
  flex-wrap: wrap;*/
  min-width: 100vh;
  text-align: center;
  margin-top: -100px;
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
