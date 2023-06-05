<script lang="ts">
    function Move() {
        
    }
</script>

<div id="top">
    <h1>Ben Lusted</h1>
    <h3>Sound Design & Implementation</h3>

    <a href="#mid">Demo Reel</a>
</div>

<style>
    #top {
        width:100vw;
        background-color: #F92A50;
        text-align: center;
        height: 100vh;

        display:flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
    }

    h1, h3 {
        margin:0;
        padding:0;
    }
    h1 {
        font-size: 120px;
        line-height: 100px;
    }
    h3 {
        font-weight: 300;
        font-size: 24px;
    }

    a {
        position:absolute;
        bottom:90px;

        font-size:24px;

        background: linear-gradient(-45deg, #e92efb, #ff4920, #440bd4, #ff1064);
        background-size: 400% 400%;
        animation: gradient 15s ease infinite;

        border: 1px solid whitesmoke;
        text-decoration: none;
        color: whitesmoke;
        padding:12px 30px;

        border-radius: 50px;

        transition: all 0.2s ease;
    }
    a:hover {
        padding: 12px 36px;
    }

    @keyframes gradient {
	0% {
		background-position: 0% 50%;
	}
	50% {
		background-position: 100% 50%;
	}
	100% {
		background-position: 0% 50%;
	}
}
</style>