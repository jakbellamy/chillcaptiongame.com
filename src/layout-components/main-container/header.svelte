<script>

</script>

<div id="container">
    <h1>CHILLCAPTIONGAME.COM</h1>
    <div id="button-div">
        <button id="btn">MUSIC</button>
        <button id="btn">FRESH</button>
    </div>
</div>

<style lang="scss">
    * {
        margin: 0;
        padding: 0;
    }
    #container {
        display: grid;
        grid-template-columns: auto auto;
        background: linear-gradient(to left, #E7C8F7, #F0D1CF);
        height: 15vh;
        width: 80vw;
        border-bottom: 1px solid #4F5254;
        vertical-align: top;
        overflow: hidden;
        margin: 0;
        padding: 0;
    }
    h1 {
        font-family: 'B612', sans-serif;
        font-size: 4.6em;
        font-weight: 100;
        margin-top: .6em;
        padding-left: .7em;
        color: #FFFFFF;
        text-shadow: 4px 6px #92839A;
    }
    #btn {
        color: #D8D8DA;
        font-family: 'Lato', sans-serif;
        font-size: 20px;
        text-decoration: none;
        text-shadow: -1px -1px 1px #616161;
        position: relative;
        padding: 20px 30px;
        -webkit-box-shadow: 5px 5px 0 #6C6A83;
        -moz-box-shadow: 5px 5px 0 #6C6A83;
        -webkit-transition: all 0.3s ease;
        -moz-transition: all 0.3s ease;
        margin: 0 10px 0 0;
    }

    #btn:hover {
        -webkit-box-shadow: 0px 0px 0 #6C6A83;
        -moz-box-shadow: 0px 0px 0 #6C6A83;
        top: 8px;
        left: 8px;
    }
    #button-div {
        text-align: right;
        margin-top: 5.3vh;
        margin-right: 1em;
    }
</style>