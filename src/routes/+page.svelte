<style>
    header {
        background-color: AntiqueWhite;
        position: fixed;
        top: 0;
        left: 0;
        right: 0;
        display: flex;
        align-items: center;
        height: 40px;
    }

    .navbar {
        display: block;
        margin-left: auto;
        margin-right: auto;
    }

    .button {
        color: black;
        background-color: AntiqueWhite;
        border: 2px solid black;
        border-radius: 4px;
        font-family: Tilt Warp;
        margin: 10px;
    }

    .button:hover {
        transform: translateY(-2px);
        border: 2px solid black;
        box-shadow: 0px 2px 0px black;
     }

     .current {
        color: white;
        background-color: black;
        border: 2px solid black;
        border-radius: 4px;
        font-family: Tilt Warp;
        margin: 10px;
    }

    .current:hover {
        transform: translateY(-2px);
        border: 2px solid black;
        box-shadow: 0px 2px 0px black;
     }

    body {
        margin-top: 60px;
        background-color: DarkSlateGrey;
        @font-face {
            font-family: 'Tilt Warp';
            src: url("C:\Users\hamst\Downloads\Mochiy_Pop_One,Tilt_Warp\Tilt_Warp\static\TiltWarp-Regular.ttf");
        }
        font-family: Tilt Warp;
    }

    div {
        display: flex;
        flex-direction: column;
        margin: auto;
        text-align: center;
        width: 25%;
        border: 40px solid AntiqueWhite;
        border-radius: 4px;
        background-color: AntiqueWhite;
    }
    
</style>

<header>
    <nav class="navbar">
        <button type="button" class="current">About Me</button> 

        <a href="src\routes\games\+page.svelte">
            <button type="button" class="button">Games</button> 
        </a>

        <a href="src\routes\art\+page.svelte">
                <button type="button" class="button">2D Art</button> 
        </a>
        
        <a href="src\routes\blender\+page.svelte">
            <button type="button" class="button">3D Art</button> 
        </a>


        <a href="src\routes\music\+page.svelte">
            <button type="button" class="button">Music</button> 
        </a>
    </nav>
</header>

<body></body>

<div>
    <h1>Hello, I'm Phil!</h1>
    <p>I'm a game developer, pixel artist, 3d modeler, and aspiring composer. I'm aiming to make a game inspired by Hollow Knight and Celeste, and currently, I'm working on a short 3D platformer!</p>

    <p>P.S. This page is a W.I.P for now, so you can't access anything else.</p>
</div>

