<script lang="ts">
  import Card from '../components/Card.svelte'
</script>

<div class="flex flex-col items-center gap-4">
  <Card />
  <Card />
  <Card />
  <Card />
  <Card class="sticky top-[50px] z-100" />
  <button
    class="px-6 py-1 bg-gray-200 text-black font-semibold rounded-full cursor-pointer sticky floating-button z-[101]"
    >Back to Top</button
  >
</div>

<style>
  .floating-button {
    top: calc(100vh - 38px);
  }
</style>
