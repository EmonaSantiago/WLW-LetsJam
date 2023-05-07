<script>
  import myImage from "/Users/emonasantiago/Documents/choices-choices-the-tech-stack/WLW-LetsJam/src/assets/Schermafbeelding 2023-03-08 om 12.53 3.png";
</script>

<section id="hero">
  <h1>WE 🤍 WEB</h1>
  <img src={myImage} alt="My Image" width="100%" />
</section>

<style>
  #hero {
    margin: 2em;
    align-content: center;
    text-align: center;
  }
  h1 {
    margin: 0;
    padding: 1em;
    position: absolute;
    color: white;
  }

  img {
    width: 100%;
    height: auto;
    border-radius: 0.5rem;
  }

  @media only screen and (max-width: 375px) {
    img {
      height: 80vh;
      object-fit: cover;
      width: 100%;
    }
  }

  @media only screen and (max-width: 375px) {
    h1 {
      font-size: 16px;
      position: absolute;
      font: "Fira Sans", sans-serif;
    }
  }
</style>
