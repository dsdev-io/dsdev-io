<svelte:head>
  <title>Projects — dsDev.io</title>
  <meta name="description" content="About this app" />
</svelte:head>

<div class="text-column">
  <h1>Personal Projects</h1>

    <section>
    <div class="project">
        <h3>Nextshot</h3>
        <ul class="tags">
            <li>Linux</li>
            <li>Desktop</li>
            <li>Bash</li>
        </ul>
    </div>
    <div class="project">
        <h3>Servidor</h3>
        <ul class="tags">
            <li>Linux</li>
            <li>Server</li>
            <li>PHP</li>
            <li>Bash</li>
            <li>Laravel</li>
            <li>Vue</li>
        </ul>
    </div>
    </section>
</div>

<style>
section { display: flex; width: 48rem; }
.project {
    border: 1px solid black;
    width: 30rem;
    margin: 0 0.5rem 0;
    padding: 0 1rem 0;
    flex-direction: left;
}
.tags {
    display: flex;
    list-style: none;
    padding: 0;
}
.tags li {
    background: yellow;
    border-radius: 4px;
    padding: 2px 5px;
    margin: 0 3px;
}
</style>
