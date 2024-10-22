<body>
    <header></header>
    
    <div id="hoveddel">
        <div id="faktiskheader">
            <a href="/flavors" class="headertext"><div class="headertext">Flavors & Recipies</div></a>
            <a href="/" class="headertext"><div class="headertext">Create new recipe</div></a>
            <a href="/aboutus" class="headertext" id="sidenduerpa"><div class="headertext">About us</div></a>
        </div>

        <div id="boks">
            
            <h1>About us 🥭 About us 🥭 About us 🥭 </h1>
            <div id="tekstogprikk">
                <div id="tekst">
                    <p>Welcome to Smooth Smoothies – your ultimate destination for all things smoothie! Whether you’re a smoothie enthusiast or just starting out, our community-driven platform is here to inspire and nourish you with endless recipe ideas.</p>
                    <p>At Smooth Smoothies, users can share their favorite smoothie creations, browse through a variety of delicious and healthy recipes, and discover new flavor combinations to fuel their days. From classic fruit blends to superfood-packed power smoothies, there’s something for every taste and lifestyle.</p>
                    <p>Our mission is simple: to create a space where everyone, from beginners to experts, can come together, exchange ideas, and celebrate the art of smoothie-making. We believe that smoothies are more than just a drink – they’re a way to bring health, creativity, and fun into your life.</p>
                    <p>Join our community today, and start blending up something smooth!</p>
                </div>
                <div id="prikk1" class="prikk"></div>
                <div id="prikk2" class="prikk"></div>
                <img id="tresmoothies" src="/aboutussmoothie.png" alt="">
            </div>
            
              
        </div>

     


        <div id="orangestripe">
            <div>Contact us:</div>
            <div>Mail: helenagrodum@icloud.com</div>
            <div>Tlf: +47  923 15 371</div> 
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
        background-color: #FCEBC1;
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
        background-color: #FCB8B9;
        margin-top: 3vh;
        border-color: #131313;
        border-width: 0.3vw;
        border-style: solid;
        border-radius: 3vw;
        display: flex;
        flex-direction: column;
        align-items: center;
        
        
    }
    


    #faktiskheader{
        height: 5vh;
        width: 85vw;
        background-color:#FCEBC1;
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
        flex-direction: column;
        justify-content: space-between;
        

        
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
        font-size: 2vw;
        
        

    }

    
    

    .headertext{
        text-decoration: none;
        color: #131313;
        
    }


    .prikk{
        width: 20vw;
        height: 20vw;
        border-radius: 50%;
        margin-top: -20vh;
        
    }

    #prikk1{
        background-color: #FFBF9B;
        margin-top: -5vw;
        
    }

    #prikk2{
        background-color: #FF9B9B;
        opacity: 50%;
        margin-left: -7vw;
    }
    

   #tekstogprikk{
        display: flex;
        flex-direction: row;
       
        
    }

    #tekst{
        width: 45vw;
        margin-top: -8vw;
        font-family: 'Bodoni Moda', serif;
        font-size: 1.3vw;
    }

    h1{
        font-size: 6vh;
    }
    
    #tresmoothies{
        position: absolute;
        width: 20vw;
       left: 62vw;
       top: 35vh;
    }


    #sidenduerpa{
        font-weight: bold;
    }
    
</style>