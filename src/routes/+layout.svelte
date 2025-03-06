<script lang="ts">
  import "../app.css";
  let { children } = $props();
</script>

<svelte:head>
  <!-- HTML Meta Tags -->
  <title>Alpine Softworks</title>
  <meta
    name="description"
    content="Developing cutting-edge software and websites with alpine precision."
  />

  <!-- Facebook Meta Tags -->
  <meta property="og:url" content="https://alpinesoftworks.cc" />
  <meta property="og:type" content="website" />
  <meta property="og:title" content="Alpine Softworks" />
  <meta
    property="og:description"
    content="Developing cutting-edge software and websites with alpine precision."
  />
  <meta
    property="og:image"
    content="https://opengraph.b-cdn.net/production/images/ea362542-4b48-42e7-bc40-c76c6fa70989.png?token=sF7kNj2vUSGZ0nlrKYU5vXniGErAHKmOlPnl6fUJgH0&height=800&width=800&expires=33277290226"
  />

  <!-- Twitter Meta Tags -->
  <meta name="twitter:card" content="summary_large_image" />
  <meta property="twitter:domain" content="alpinesoftworks.cc" />
  <meta property="twitter:url" content="https://alpinesoftworks.cc" />
  <meta name="twitter:title" content="Alpine Softworks" />
  <meta
    name="twitter:description"
    content="Developing cutting-edge software and websites with alpine precision."
  />
  <meta
    name="twitter:image"
    content="https://opengraph.b-cdn.net/production/images/ea362542-4b48-42e7-bc40-c76c6fa70989.png?token=sF7kNj2vUSGZ0nlrKYU5vXniGErAHKmOlPnl6fUJgH0&height=800&width=800&expires=33277290226"
  />
</svelte:head>

{@render children()}
