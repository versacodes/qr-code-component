<script setup>

</script>

<template>
  <main>
    <img src="./images/image-qr-code.png" />
    
    <h1>Improve your front-end skills by building projects</h1>

    <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
    
    <div class="attribution">
      Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>.
      Coded by <a href="https://github.com/versacodes">Franz Amersian Tiongson</a>.
    </div>
  </main>
</template>

<style scoped>
main {
  max-width: 90%;
  background: hsl(0, 0%, 100%);
  margin: 0 auto;
  padding: 1.5rem;
  border-radius: 15px;
}

img {
  border-radius: 15px;
}

h1,p {
  font-family: 'Outfit', monospace;
  text-align: center;
  margin-top: 15px;
  font-size: 1.5rem;
  padding: 0 1rem;
}

h1 {
  color: hsl(218, 44%, 22%);
  font-weight: 700;
}

p {
  font-size: 15px;
  font-weight: 400;
  color: hsl(220, 15%, 55%);
  margin-bottom: 15px;
}

.attribution {
  padding: 5px 0;
  font-size: 0.9rem;
}

@media only screen and (min-width: 600px) {
  h1 {
    font-size: 2rem;
  }

  p {
    font-size: 1.1rem;
  }

  main {
    max-width: 450px;
  }
} 
</style>
