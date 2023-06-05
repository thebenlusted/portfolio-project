<script>
    import IoLogoLinkedin from 'svelte-icons/io/IoLogoLinkedin.svelte'
    import IoLogoTwitter from 'svelte-icons/io/IoLogoTwitter.svelte'
    import IoLogoVimeo from 'svelte-icons/io/IoLogoVimeo.svelte'
</script>

<footer>
    <p><b>Ben Lusted</b><br>Sound Design & Implementation</p>
    <br />
    <div class="icon">
        <a href="https://www.linkedin.com/in/benlusted/" target="_blank"><IoLogoLinkedin /></a>
    </div>
    <div class="icon">
        <a href="https://twitter.com/benlustedaudio" target="_blank"><IoLogoTwitter /></a>
    </div>
    <div class="icon">
        <a href="https://vimeo.com/benlustedaudio" target="_blank"><IoLogoVimeo /></a>
    </div>
</footer>

<style>
    footer {
        width:100%;
        padding:50px 0;
        color: whitesmoke;
        font-size:16px;
        font-weight: 200;
        text-align: center;

        background-color: #07030B;
    }

    .icon {
        width:30px;
        height:30px;

        display:inline-block;
        margin:0 10px;
    }

    a {
        text-decoration: none;
        color: whitesmoke;
    }
</style>