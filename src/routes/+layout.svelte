<script>
  import Header from './components/Header.svelte';
  import Footer from './components/Footer.svelte';
</script>

<Header />

<main>
  <slot />
</main>

<Footer />

<style>
/* Ваши стили */
</style>
