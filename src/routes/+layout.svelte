<script>
  import Header from './Header.svelte';
  import './styles.css';
</script>

<div class="app">
  <Header />

  <main>
    <slot />
  </main>

  <footer>
    <small>
      This is not the greatest page in the world; this is just a
      <a href="https://www.youtube.com/watch?v=_lK4cX5xGiQ">Tribute</a>.
    </small>
  </footer>
</div>

<style>
  .app {
    display: flex;
    flex-direction: column;
    min-height: 100vh;
  }

  main {
    flex: 1;
    display: flex;
    flex-direction: column;
    padding: 1rem;
    width: 100%;
    max-width: 64rem;
    margin: 0 auto;
    box-sizing: border-box;
  }

  footer {
    display: flex;
    flex-direction: column;
    justify-content: center;
    text-align: center;
    align-items: center;
    padding: 12px;
  }

  footer a {
    font-weight: bold;
  }

  @media (min-width: 480px) {
    footer {
      padding: 12px 0;
    }
  }
</style>
