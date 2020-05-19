<script>
import Game_1 from './game-1.svelte'
import Game_2 from './game-2.svelte'
</script>

<div id="square">
    <Game_1 />
</div>

<style>
    * {
        margin: 0;
        padding: 0;
    }
    #square {
        display: grid;
        grid-template-columns: auto auto;

        height: 39vh;
        width: 40vw;
        background-color: #C8C7CA;
        background: #ffffff;
        border-radius: 5px;
        margin-top: 1vh;
        margin-left: 21.8vw;
        box-shadow:
                0 2.8px 2.2px rgba(0, 0, 0, 0.034),
                0 6.7px 5.3px rgba(0, 0, 0, 0.048),
                0 12.5px 10px rgba(0, 0, 0, 0.06),
                0 22.3px 17.9px rgba(0, 0, 0, 0.072),
                0 41.8px 33.4px rgba(0, 0, 0, 0.086),
                0 100px 80px rgba(0, 0, 0, 0.12);
        min-height: 200px;
        opacity: 0.5;
        text-align: center;
        padding: 2vh;
        padding-top: 3.5vh;
        border: 2px solid #4B4956;
    }
</style>