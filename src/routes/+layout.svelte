<script>
  import Header from '$lib/components/layouts/header.svelte';
  import Footer from '$lib/components/layouts/footer.svelte';
</script>

<Header />
<main class="content">
  <slot />
</main>
<Footer />

<style>
  .content {
    margin-top: 80px; /* ヘッダーの高さ分 */
    /* padding: 20px;  */
  }
</style>
