<template>
  <div id="home" class="static-design-bg">
    <div class="container">
      <div class="content">
        <div class="picture"></div>
        <br>
        <strong><h1 class="text">Hi! I'm palmes</h1></strong>
        <div class="text-container">
          <p class="text">I am Palmes, a BSIT student, living fully committed to striving for a better life.
            <br>Fatigue means nothing to me as long as,
            <br>I achieve my life goals of completing my studies and excelling in my academics.</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
#home {
  height: 100vh;
  width: 100vw;
  display: flex;
  justify-content: center;
  align-items: center;
  overflow: hidden;
}

.container {
  text-align: center;
}

.content {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.picture {
  width: 200px;
  height: 200px;
  background-color: rgba(173, 216, 230, 0.7); /* Change background color here */
  background-image: url('@/assets/palmes.jpg');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  border-radius: 50%;
  margin-bottom: 20px;
}

.text {
  margin: 0;
}

.text-container {
  overflow: hidden;
  white-space: nowrap;
}

.text-container p {
  animation: textScroll 20s linear infinite; /* Adjust the speed and duration of the animation as needed */
}

@keyframes textScroll {
  0% {
    transform: translateX(100%);
  }
  100% {
    transform: translateX(-100%);
  }
}

/* Static background */
.static-design-bg {
  background-color: #4682B4; /* Change background color here */
  margin: 0;
  padding: 0;
}
</style>
