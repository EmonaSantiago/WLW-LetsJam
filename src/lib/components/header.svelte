<script>
  import logo from "/Users/emonasantiago/Documents/choices-choices-the-tech-stack/WLW-LetsJam/src/assets/Schermafbeelding 2023-03-15 om 18.46 3 (1).png";
</script>

<header>
  <p>
    <a href="/">
      <img src={logo} alt="My Image" width="100%" />
    </a>
  </p>

  <ul>
    <li class="aanmelden-btn"><a href="/aanmelden">Aanmelden</a></li>
    <li class="fdnd-btn"><a href="https://fdnd.nl/">FDND.nl</a></li>
  </ul>
</header>

<style>
  a {
    color: white;
    text-decoration: none;
  }

  img {
    width: 8em;
    float: left;
    margin-left: 1.5em;
  }

  ul {
    float: right;
  }

  .aanmelden-btn {
    border: solid #a675f5 1px;
  }

  .fdnd-btn {
    border: solid #66e5bf 1px;
    color: #050542;
  }
  li {
    display: inline-block;
    border-radius: 0.5rem;
    margin: 0.2rem;
    padding: 0.6rem 1.2rem;
  }

  @media only screen and (max-width: 375px) {
    img {
      width: 5em;
      margin-top: 1em;
      margin-left: 1.5em;
    }

    li {
      display: inline-block;
      border-radius: 0.5rem;
      padding: 0.5em;
    }
  }
</style>
