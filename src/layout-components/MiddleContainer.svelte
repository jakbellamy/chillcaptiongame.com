<script>
    import Header from "./main-container/header.svelte"
    import Body from "./main-container/body.svelte"
    import Footer from "./main-container/footer.svelte"
</script>

<div id="container">
    <Header />
    <Body />
    <Footer />
</div>

<style lang="scss">
    #container {
        background-color: #E5E5E5;
        grid-template-rows: 10vh auto 5vh;
        width: auto;
        height: 99vh;
        /*border: 5px solid #4E0376;*/
    }
</style>