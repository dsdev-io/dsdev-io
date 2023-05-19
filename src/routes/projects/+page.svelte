<svelte:head>
  <title>Projects — dsDev.io</title>
  <meta name="description" content="About this app" />
</svelte:head>

<div class="text-column">
  <h1>Personal Projects</h1>

  <section>
    <div class="project">
      <h3>Nextshot</h3>
      <p>A minimal screenshot tool that can upload to NextCloud.</p>
      <hr />
      <ul class="tags">
        <li>Linux</li>
        <li>Bash</li>
      </ul>
    </div>
    <div class="project">
      <h3>Servidor</h3>
      <p>Linux server admin panel, created purely to learn Vue.</p>
      <hr />
      <ul class="tags">
        <li>Linux</li>
        <li>Bash</li>
        <li>PHP</li>
        <li>Laravel</li>
        <li>Vue</li>
      </ul>
    </div>
  </section>
</div>

<style>
  section {
    display: flex;
    width: 59rem;
  }
  .project {
    background: var(--color-bg-2);
    border: 1px solid var(--color-bg-0);
    width: 30rem;
    margin: 0 0.5rem 0;
    padding: 0 1rem 0;
    flex-direction: left;
  }
  .tags {
    display: flex;
    font-family: var(--font-mono);
    list-style: none;
    padding: 0;
  }
  .tags li {
    background: var(--color-bg-2);
    border: 1px solid var(--color-bg-0);
    border-radius: 4px;
    color: var(--color-theme-2);
    cursor: default;
    padding: 4px 5px 2px;
    margin: 0 3px;
  }
  hr {
    border-top: 1px solid var(--color-bg-0);
    margin-left: -2.5%;
    padding: 0;
    width: 105%;
  }
</style>
