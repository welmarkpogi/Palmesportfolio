<template>
  <div class="container">
    <div class="profile-wrapper">
      <img src="@/assets/palmes.jpg" alt="Profile Image" class="profile-image">
    </div>
    <strong>
      <p class="blue-text">Hi! I am Rechelle, a girl who continues dreaming in life. With a vibrant passion for innovation and problem-solving, I am a force to be reckoned with. With a heart set on pursuing excellence in the realm of information technology, 
        <br>I exude determination and drive in every endeavor I undertake. My insatiable thirst for knowledge and my unwavering commitment to craft propel me forward, inspiring those around me to reach greater heights. My journey is marked by my relentless pursuit of growth and unwavering dedication to making a meaningful impact through my work.
      </p>
    </strong>
  </div>
</template>

<style scoped>
.container {
  background: linear-gradient(to bottom, #e017aa, #4682B4); 
  background-size: cover; 
  background-repeat: no-repeat; 
  background-position: center; 
  height: 100vh; /* Full height of viewport */
  width: 100vw; /* Full width of viewport */
  padding: 100px 0; /* Adjust vertical padding */
  border-radius: 10px;
  color: #333; 
  background-color: rgba(255, 255, 255, 0.7);
  display: flex; /* Use flexbox */
  flex-direction: column; /* Arrange items vertically */
  justify-content: center; 
  align-items: center; 
}

.profile-wrapper {
  text-align: center; /* Align the text to the center */
}

.profile-image {
  width: 150px; /* Adjust image width as needed */
  height: 150px; /* Adjust image height as needed */
  border-radius: 50%; /* Make image round */
  margin-bottom: 20px; /* Add margin below image */
}

.blue-text {
  color: black; 
}
</style>
