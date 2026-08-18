<script lang="ts">
  import '../app.css';

  let { children } = $props();
</script>

<svelte:head>
  <meta name="description" content="A fast, accessible SvelteKit website." />
  <meta property="og:site_name" content="Example" />
  <meta property="og:type" content="website" />
  <meta property="og:title" content="Example" />
  <meta property="og:description" content="A fast, accessible SvelteKit website." />
  <meta property="og:url" content="https://example.com" />
</svelte:head>

{@render children()}
