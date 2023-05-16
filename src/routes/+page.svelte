<svelte:head>
  <title>Home — dsDev.io</title>
  <meta name="description" content="I code things. These are some of those things." />
</svelte:head>

<section>
  <h1>
    <span class="hi">Hi!</span>
    I'm Dave. I code things.
  </h1>
</section>

<style>
  section {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    flex: 0.6;
  }

  h1 {
    width: 100%;
  }

  .hi {
    display: block;
    font-size: 300%;
    position: relative;
    width: 100%;
    height: 0;
    padding: 0 0 calc(70% * 495 / 2048) 0;
  }
</style>
