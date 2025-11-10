<stylesheet>
    body, html {
        height: 100%;
    }

    /* The hero image */
    .hero-image {
    /* Use "linear-gradient" to add a darken background effect to the image (photographer.jpg). This will make the text easier to read */
    background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url("photographer.jpg");

    /* Set a specific height */
    height: 50%;

    /* Position and center the image to scale nicely on all screens */
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
    }

    /* Place text in the middle of the image */
    .hero-text {
    text-align: center;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white;
    }
</stylesheet>
<div class="hero-image">
  <div class="hero-text">
    <h1>D O N K</h1>
    <p>Welcome to the Official GitHub Repository for the development and documentation of the game "D O N K"</p>
    <p>"D O N K" is a singleplayer 3D tank simulator where the user plays against a Machine Learning agent as it develops and trains itself off the user movement</p>
    <button>Hire me</button>
  </div>
</div>