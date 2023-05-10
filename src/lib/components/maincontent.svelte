<script>
  import Introduction from "./Introduction.svelte";
  import Sessions from "./Sessions.svelte";
</script>

<div class="row">
  <div class="left-column">
    <Introduction />
  </div>
  <div class="right-column">
    <Sessions />
  </div>
</div>

<style>
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
</style>
