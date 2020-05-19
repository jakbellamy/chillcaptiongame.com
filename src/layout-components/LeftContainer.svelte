<script>

</script>

<div id="container">
    <h1>CAPTIONS</h1>
    <div id="content">

    </div>
</div>

<style lang="scss">
    * {
        margin: 0;
        padding: 0;
    }
    #container {
        display: grid;
        grid-template-rows: 4vh 4vh 4vh 4vh 4vh;
        width: auto;
        height: 99vh;
        border-right: 1px solid #B3B8BA;
        text-align: center;
        background: repeating-radial-gradient(circle at 99%, rgba(222, 212, 202, 0.51), rgba(29, 20, 69, 0.49) 1.7px);
    }
    h1 {
        font-family: 'Inconsolata', monospace;
        font-size: 2.8em;
        letter-spacing: 0.4em;
        margin: 20px;
        text-shadow: -1px 3px #ffffff;
        border-left: 1px solid #ffffff;
        border-right: 1px solid #ffffff;
        /*width: 10vw;*/
        color: rgba(104, 168, 210, 0.85);
    }
    #content {
        height: 75vh;
        margin-top: 5.8vh;
        /*width: 16vw;*/
        /*margin-left: 1vw;*/
        /*margin-right: 1vw;*/
    }
    #item{
        display: grid;
        grid-template-columns: 3vw 7vw;
        text-align: left;
    }
    #usr{
        font-family: 'Inconsolata', monospace;
        font-size: 1.2em;
        margin-left: 1vw;
        color: #B01F04;
        text-shadow: 0px 1px #e5dcdc;
        background-color: #C8DBE8;
    }
    #msg{
        margin-left: 1vw;
        font-family: 'Inconsolata', monospace;
        font-size: 1.2em;
        color: #ffffff;
        text-shadow: 0px 1px #000000;
        background-color: #C8DBE8;
    }
</style>