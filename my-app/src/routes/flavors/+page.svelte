<body>
    <header></header>
    
    <div id="hoveddel">
        <div id="faktiskheader">
            <a href="/flavors" class="headertext" id="sidenduerpa"><div class="headertext">Flavors & Recipies</div></a>
            <a href="/" class="headertext"><div class="headertext">Create new recipe</div></a>
            <a href="/aboutus" class="headertext"><div class="headertext">About us</div></a>
        </div>

        <div id="boks">
            
            <div id="bildeboks">
                <img id="bilde1" src="https://i.pinimg.com/474x/42/0d/bc/420dbc0050b6e5c0ff5703ffa6291fe9.jpg" alt="">
                <img id="bilde1" src="https://i.pinimg.com/564x/1b/ee/dc/1beedc0b7a63a3091ee6cdb1f2bc9eb3.jpg" alt="">
                
            </div>

            <div id="tekstboks">
                <div id="mainSmoothieTitel">Amezzzzing Mango</div>
                <div id="fruktEmojie">🥭🥭🥭</div>
                <button id="gotor">Go To Recipe</button>
                <div id="piler">
                    <a class="pil" href="/"><div>🔙</div></a>
                    <a class="pil" href="/"><div>🔜</div></a>
                </div>
            </div>
            
        </div>

     


        <div id="orangestripe">
            <div>Mango</div>
            <div id="prikk">⬤</div> 
            <div>Banana</div>
            <div id="prikk">⬤</div> 
            <div>Applejuice</div>
            <div id="prikk">⬤</div> 
            <div>Lime</div>
            <div id="prikk">⬤</div>
            <div>Coconutmilk</div> 
                
           

        </div>

        
        
        
        
        
    </div>
    
    <div id="sortering">
        <div>Random</div>
        <div>Popular</div>
        <div>Newest</div>

    </div>

    <div id="smaker">
        <div>Strawberry</div>
        <div>Mango</div>
        <div>Rasberry</div>
        <div>Orange</div>
        <div>Banana</div>
        <div>Coconut</div>
        <div>Spinach</div>

    </div>


    <div id="topsmoothies">

        <div id="smoothieFlex">
            <div id="smoothie1" class="smothieboks">
            <img class="smoothiebilde" src="https://i.pinimg.com/564x/69/bb/5d/69bb5db4795717deec9189ba7d3b0210.jpg" alt="smoothiebilde" >
            <div>
                <div class="smothietitel">Rasberry Dream</div>
                <div class="ingridienser">Raspberry, strawberry, vanilla yogurt</div>
                <button id="gotor2">Go to recipe</button>
            </div>

            </div>
            <div id="smoothie2" class="smothieboks">
                <img class="smoothiebilde" src="https://i.pinimg.com/564x/3f/65/d2/3f65d2a6c4271972781f0184f15043c0.jpg" alt="smoothiebilde" >
                <div>
                    <div class="smothietitel">Kiwi Dream</div>
                    <div class="ingridienser">Kiwi, Papaya, Banana</div>
                    <button id="gotor2">Go to recipe</button>
            </div>
        </div>
        

    </div>
</body>


<style>

    @font-face {
        font-family: 'Crimson Pro';
        src: url('https://fonts.gstatic.com/s/crimsonpro/v8/q5uCsoe5IOB2-pXv9UcNI4t3FCsbPrU.woff2') format('woff2'),
             url('https://fonts.gstatic.com/s/crimsonpro/v8/q5uCsoe5IOB2-pXv9UcNI4t3FCsbPrU.woff') format('woff');
        font-weight: 400;
        font-style: normal;
    }

    @font-face {
    font-family: myBodoni;
    src: url(bodoni-variable.ttf); 
    }

    
    body{
        background-color: #F1B641;
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 0px;
        margin: 0px;
        font-family: 'Bodoni Moda', serif;
        
    }

    header{
        width: 100vw;
        height: 7vh;
        background-color: #131313;
        
        
    }

    #hoveddel{
        width: 90vw;
        height: 80vh;
        background-color: #FCECC1;
        margin-top: 3vh;
        border-color: #131313;
        border-width: 0.3vw;
        border-style: solid;
        border-radius: 3vw;
        display: flex;
        flex-direction: column;
        align-items: center;
        
        
    }
    
    #sortering{
        width: 90vw;
        height: 12vh;
        background-color: #FCECC1;
        margin-top: 5vh;
        border-style: solid;
        border-color: #131313;
        border-width: 2px;
        border-radius: 3vw;
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: space-around;
        font-family: 'Bodoni Moda', serif;
        font-size: xx-large;
        
    }
    
    #smaker{
        width: 90vw;
        height: 7vh;
        background-color: #FCECC1;
        margin-top: 1vh;
        border-style: solid;
        border-color: #131313;
        border-width: 2px;
        border-radius: 2vw;
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: space-around;
        font-family: 'Bodoni Moda', serif;
        font-size: large;
        
    }

    #faktiskheader{
        height: 5vh;
        width: 85vw;
        background-color:#F2BABB;
        border-radius: 2vw;
        margin-top: 1.5vw;
        display: flex;
        justify-content: space-evenly;
        align-items: center;
        font-family: 'Bodoni Moda', serif;
    }

    #boks{
        margin-top: 2vh;
        width: 85vw;
        height: 70vh;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;

        
    }

   


    #orangestripe{
        width: 90vw;
        height: 10vh;
        background-color: #F07C5F;
        border-radius: 0 0 3vw 3vw;
        display: flex;
        flex-direction: row;
        justify-content: space-around;
        align-items: center;
        font-family: 'Bodoni Moda', serif;
        font-size: xx-large;
        
        

    }

    
    

    .headertext{
        text-decoration: none;
        color: #131313;
        
    }


    #bildeboks{
        width: 60%;
        height: 50vh;
        background-color: #F2DE4E;
        border-radius: 3vw;
        border-style: solid;
        border-width: 0.3vw;
        border-color: #131313;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    #tekstboks{
        width: 35%;
        height: 50vh;
        border-radius: 3vw;
        border-style: solid;
        border-width: 0.3vw;
        border-color: #131313;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }

    #prikk{
        font-size: medium;
    }

    #bilde1{
        height: 40vh;
        width: auto;
        margin: 2vw;
        border-radius: 2vw;
    }

    .pil{
        text-decoration: none;
        margin-left: 0.5vw;
        margin-right: 0.5vw;
        
        
    }

    #piler{
        display: flex;
        flex-direction: row;
        font-size: 3vw;
        margin-top: 1vw;
        margin-bottom: -2vw;
    
        
    }

    #mainSmoothieTitel{
        font-family: 'Bodoni Moda', bold;
        text-align: center;
        font-size:4vw;
        width: 90%;
    }

    #fruktEmojie{
        font-size: xx-large;
    }

    #gotor{
        background-color: #FCECC1;
        color: black;
        border-color: black;
        width: 16vw;
        border-radius: 1vw;
        height: 5vh;
        margin-top: 3vh;
        font-family: 'Bodoni Moda', bold;
        font-size: large;
    }

    .smothieboks{
        width: 40vw;
        height: 50vh;
        border-style: solid;
        border-color: #131313;
        border-width: 2px;
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: space-around;
        border-radius: 4vw;
        margin-top: 3vh;
    }

    .smoothiebilde{
        height: 40vh;
        width: auto;
        border-radius: 6vw;
    }

    .smothietitel{
        font-family: 'Bodoni Moda', bold;
        font-size: 5.5vh;
        margin-top: 1.5vh;
    }

    #topsmoothies{

        display: grid;
        grid-template-columns: repeat(3, 1fr); 
        gap: 15px; 
        width: 90vw;
        display: flex;
        justify-content: space-between;
    }


    #smoothie1{
        background-color: #EEA9AB;
    }
    #smoothie2{
        background-color: #96a856;
    }

    #gotor2{
        background-color: #feffff;
        color: black;
        border-color: black;
        width: 16vw;
        border-radius: 1vw;
        height: 5vh;
        margin-top: 3vh;
        font-family: 'Bodoni Moda', bold;
        font-size: large;
    }

    #sidenduerpa{
        font-weight: bold;
    }

    
</style>