<script>
    import "$root/app.css";
    import Header from "$containers/Header.svelte";
    import Footer from "$containers/Footer.svelte";
</script>
<div>
    <Header />
    <slot />
    <Footer />
</div>