<script land="ts">
    import Spacer from './Spacer.svelte';
</script>

<div id="mid">
    <div id="content">
        <h1>Demo Reel</h1>
        <iframe title="Demo Reel" src="https://player.vimeo.com/video/833272477?h=1ea64ee52d" width="854" height="480" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen class="reel"></iframe>

        <p>Visual content shown in this video belongs to their respective copyright holder.</p>
        <Spacer spacerHeight="90px" />

        <h2 id="wwisedemo-h">Wwise Demo</h2>
        <div id="wwisedemo">
            <p style="text-align: left; font-size:22px; grid-column: 1;">Demonstration of Audiokinetic's Wwise, the use of SoundCaster Sessions, States, Switches, RTPC's and Game Parameters</p><br />
            <iframe class="wwise-vid" title="Wwise Demonstration" src="https://player.vimeo.com/video/829795888?h=13db48ad7c" width="426" height="240" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>
        </div>
    </div>
</div>

<style>
    #mid {
        background-color: #F2F2F2;
        width:100vw;
        text-align: center;
    }
    #content {
        max-width: 854px;
        margin:0 auto;
        padding:30px 0;
    }
    p {
        color: #07030B;
        text-align: right;
        margin:0; padding:0;
        font-weight: 100;
    }
    h1 {
        text-align: left;

        color: #07030B;
        font-size:70px;
        font-weight: 900;

        padding:0;
        margin: 0;
    }
    h2 {
        text-align: left;

        color :#07030B;
        font-size: 42px;
        font-weight: 900;
        padding:0;
        margin:0;
    }

    @media screen and (max-width: 910px) {
        #content {
            padding:0;
        }
        .reel {
            max-width: 90vw;
            min-width: 300px;
        }
        h1 {
            text-align: center !important;
        }
        p {
            text-align: center !important;
        }

        .wwise-vid {
            max-width:90vw;
        }
        #wwisedemo p {
            text-align: center !important;
            max-width: 90vw;
        }
        #wwisedemo-h {
            text-align: center !important;
        }
    }
</style>