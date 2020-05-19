<script>
import GameContainer from './Game/game-container.svelte'
</script>

<div id="container">
    <h1 id="header">\CAPTION\\GAME\</h1>
    <GameContainer />
</div>

<style lang="scss">
    * {
        margin: 0;
        padding: 0;
    }
    #container {
        background:
                repeating-radial-gradient(
                                circle at 0 0,
                                #C8DBE8,
                                #CF83C1 2px
                );
        height: 79vh;
        width: 80vw;
        overflow: hidden;
        align-content: center;
    }
    #header {
        font-family: 'Inconsolata', monospace;
        font-size: 3em;
        font-weight: 100;
        margin-top: 3em;
        text-align: center;
        color: #B01F04;
        text-shadow: -1px 0px #0495B0;
        /*border: 1px solid #212121;*/
        margin-left: 27.5vw;
        width: 10em;
        overflow: hidden;
        /*text-shadow: 4px 6px #92839A;*/
    }
</style>