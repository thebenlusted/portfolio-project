<script lang="ts">

</script>

<div id="bot">
    <h1>Skills</h1>
    <table>
        <tr>
            <th class="line-bot">Game Design</th>
            <th class="line-bot">Audio Software</th>
            <th class="line-bot">Audio Production</th>
            <th class="line-bot">Programming</th>
        </tr>
        <tr>
            <td>FMOD/Wwise</td>
            <td class="line-left">Reaper/Pro Tools</td>
            <td class="line-left">Field Recordings</td>
            <td class="line-left">Javascript, HTML, CSS</td>
        </tr>
        <tr>
            <td>Unreal Engine/Unity</td>
            <td class="line-left">Waves Suite</td>
            <td class="line-left">Mixing/Mastering</td>
            <td class="line-left">Max/MSP</td>
        </tr>
        <tr>
            <td>Interactive Music</td>
            <td class="line-left">Izotope Suite</td>
            <td class="line-left">Dialogue Editing</td>
            <td class="line-left">Python</td>
        </tr>
        <tr>
            <td>Sound Design</td>
            <td class="line-left">Melda Suite</td>
            <td class="line-left">Music Production</td>
            <td class="line-left">C#/Blueprint</td>
        </tr>
    </table>

    <a href="https://docs.google.com/document/d/1eXjs4JMQKO0oH2NX3qR3u25c_F4dWCrgIPgK5yJNCoI/edit?usp=sharing" target="_blank">Resume</a>
</div>

<style>
    #bot {
        width:100vw;
        background-color: #F92A50;
        text-align: center;
        height: 100vh;

        position: relative;

        display:flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    table {
        margin: 0 auto;
    }
    table, th, td {
        padding:10px 8px;
        border-spacing: 0;
    }
    .line-left {
        border-left:1px solid whitesmoke;
    }
    .line-bot {
        border-bottom: 1px solid whitesmoke;
    }

    h1 {
        margin:0;
        padding:30px 0;
        font-size:70px;
    }

    a {
        position:absolute;
        bottom:25px;

        font-size:20px;

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

    @media screen and (max-width: 910px) {
        #bot {
            display:none;
        }
    }
</style>