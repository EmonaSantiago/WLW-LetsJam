<script>
  import myImage from "/Users/emonasantiago/Documents/choices-choices-the-tech-stack/WLW-LetsJam/src/assets/Schermafbeelding 2023-03-08 om 12.53 3.png";
  import Sessioncard from "/Users/emonasantiago/Documents/choices-choices-the-tech-stack/WLW-LetsJam/src/lib/components/Sessioncard.svelte";
</script>

<section id="hero">
  <h1>WE 🤍 WEB</h1>
  <img src={myImage} alt="My Image" width="100%" />
</section>

<div class="row">
  <div class="left-column">
    <section id="introduction">
      <p>
        Kom een Sessie volgen waarin een<br />
        designer/devloperuit de praktijk iets komt vertellenen laten zien!
      </p>
      <a href="#" class="button">WE 🤍 WEB</a>
    </section>
  </div>
  <div class="right-column">
    <Sessioncard />
  </div>
</div>

<section id="content">
  <h2>CONTENT images</h2>
</section>

<style>
  #content {
    color: white;
  }
  #introduction {
    margin-top: 2em;
    font-weight: bold;
  }

  p {
    color: white;
  }

  a {
    color: #050542;
    border: solid 1px #66e5bf;
    border-radius: 0.5rem;
    padding: 0.6rem 1.2rem;
    text-decoration: none;
    background-color: #66e5bf;
    font-weight: bold;
  }

  @media screen and (min-width: 600px) {
    p {
      font-size: 3em;
    }
  }
  * {
    box-sizing: border-box;
  }
  .row {
    height: 100vh;
    margin: auto;
    margin-top: 8em;
  }

  .left-column {
    float: left;
    width: 30%;
    padding: 2em;
    align-items: center;
    vertical-align: center;
    height: 100%;
  }

  .right-column {
    float: left;
    width: 70%;
    align-items: center;
    vertical-align: center;
    height: 100%;
  }

  .row:after {
    display: table;
    clear: both;
  }

  @media screen and (max-width: 600px) {
    .row {
      height: 100%;
    }

    .left-column {
      width: 100%;
      height: auto;
    }

    .right-column {
      width: 100%;
    }
  }
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
    background-color: #050542;
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
