<script lang="ts">
  import Posts from '$lib/Posts.svelte'
  import Headlines from '$lib/Headlines.svelte'
  import Wrapper from '../components/Wrapper.svelte'
</script>

<svelte:head>
  <!-- Primary Meta Tags -->
  <title>Clonedit</title>
  <meta name="title" content="Clonedit" />
  <meta name="description" content="Reddit layout clone" />
  <meta name="keywords" content="Svelte, SvelteKit, Svelte-kit, Tailwind, HTML, CSS, JavaScript" />
  <meta name="author" content="@dansvel" />
  <!-- Open Graph / Facebook -->
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://metatags.io/" />
  <meta property="og:title" content="Clonedit" />
  <meta property="og:description" content="Reddit layout clone" />
  <meta property="og:image" content="https://sveltekit-tailwind2.netlify.app/screenshot.png" />

  <!-- Twitter -->
  <meta property="twitter:card" content="summary_large_image" />
  <meta property="twitter:url" content="https://metatags.io/" />
  <meta property="twitter:title" content="Clonedit" />
  <meta property="twitter:description" content="Reddit layout clone" />
  <meta property="twitter:image" content="https://sveltekit-tailwind2.netlify.app/screenshot.png" />
</svelte:head>

<Wrapper>
  <div class="grid grid-cols-4 w-full gap-4 mt-4">
    <Posts />
    <Headlines />
  </div>
</Wrapper>

<style lang="postcss">
</style>
