<template>
  <div class="container">
    <div>
<center>
  <img src="minecraft.svg" alt="logo" class="w-32" />
</center>

      <h1 class="title">
        snapcraft
      </h1> 
      <div class="subtitle">minecraft for free</div>
      <div class="links">
        <a
          href="https://tlauncher.org/en/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          TLauncher
        </a>
        <a
          href="https://www.java.com/en/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--blue"
        >
          Java (only for laptops and desktops)
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 70px;
  color: #007bff;
  letter-spacing: 1px;
}


.subtitle {
  font-weight: 300;
  font-size: 32px;
  color: #00a34c;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
