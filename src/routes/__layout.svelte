<script lang="ts">
  import '../global.postcss'
  import Navbar from '$lib/Navbar.svelte'
</script>

<Navbar />
<main>
  <slot />
</main>
