<script>
    import '../app.css';
    import Footer from "$lib/components/footer/index.svelte"
    import Header from "$lib/components/header/index.svelte"
    /** @type {import('./$types').LayoutData} */
    // export let data;
</script>

<Header/>
    <slot />
<Footer />