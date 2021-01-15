<!DOCTYPE html>

<html> 

    <head> 
        <meta charset="UTF-8">
        <title>FinalProject - Home</title>

        <style> 
        #header
        {
            text-align: center;
            font-weight: bold;
            font-family: 'Courier New', Courier, monospace;
            background-color: darkred;
            color: antiquewhite;
            padding: 10px;
        }
        #body 
        {
            background-color: lightblue;
            margin: 0;
        }

        #mainpic 
        {
            width: 100%;
            height: 375px;
        }
        .h1 
        {
            text-align: center;
            font-family: 'Courier New', Courier, monospace;
            font-size: 24px;
            color: darkred;
        }
        .DestinationsPic 
        {
            width: 500px;
            padding: 10px;
            height: 275px;

        }

        .footerPic 
        {
            
            width: 494px ;
            padding: 3px;
            margin-left: 10px;
            text-align: center;
            font-family: 'Courier New', Courier, monospace;
            color: darkred;
            font-weight: bold;
            font-size: 18px;
          
        }

        #footer 
        {
            background-color: darkred;
           
            padding: 3px;
           
            text-align: center;
            font-family: 'Courier New', Courier, monospace;
            color: white;
            
           
        }
        .link 
        {
            color: white;
        }

        .column 
            {
            float: left;
            margin-left: 75px;
            padding: 5px;
            
            }

    /* Clearfix (clear floats) */
         .row::after {
                content: "";
                clear: both;
                display: table;
                     }
        </style>


    </head>

    <body id="body"> 
        <header id="header">
            <nav id="navbar">
                <span class="span"><u><a class="link" href="Home.html">TRIPS</a></u></span>
                
                <span class="span"><u><a class="link" href="About.html" target="_blank">ABOUT</u></span></a>
                <span class="span"><u><a class="link" href="Contact.html" target="_blank">CONTACT</a></u></span>
            </nav>
        </header>

        <div>
            <img id="mainpic" src="https://www.travelprofessionalnews.com/wp-content/uploads/2019/12/he-Dominican-Republic-Ministry-of-Tourism-Implements-Ambitious-Media-Relations.jpg"
             alt="DR has it all">

             
        </div>

        <div> 
            <h1 class="h1"> My Travel Diary </h1>
        </div>

        <div class="row"> 
            <div class="column">
                <a href="https://www.godominicanrepublic.com/poi/beaches/pedernales/bahia-de-las-aguilas-2/" target="_blank"> <img class="DestinationsPic" src="https://i.pinimg.com/originals/7a/5f/39/7a5f39a0c4abe79b0929cdf5b69ea797.jpg"
                 alt="Bahia de las aguilas" > </a>
                 <footer class="footerPic"> Bahia de las Águilas</footer>
            </div>

            <div class="column">
                <a href="https://www.tripadvisor.com/Attraction_Review-g1761612-d17801940-Reviews-Pozos_ecologicos_de_Romeo_Frances-Pedernales_Pedernales_Province_Dominican_Repu.html" target="_blank">
                <img class="DestinationsPic" src="https://idominicanas.com/wp-content/uploads/2018/12/Los-pozos-ecologicos-de-romeo-en-pedernales-by-Where-Is-Beatriz.jpg"
                alt="Pozos ecologicos de romeo" > </a>
                <footer class="footerPic"> Pozos ecológicos de Romeo</footer>
           </div> 

           <div class="row"> 
            <div class="column">
                <a href="https://www.godominicanrepublic.com/poi/family/jarabacoa/armando-bermudez-national-park/" target="_blank" >
                 <img class="DestinationsPic" src="https://www.godominicanrepublic.com/wp-content/uploads/2018/03/valle-del-lil-s_1.jpg"
                 alt="J. Armando Bermudez" > </a>
                 <footer class="footerPic"> J. Armando Bermudez, National Park</footer>
            </div>

            <div class="column">
                <a href="https://www.godominicanrepublic.com/poi/bird-watching/samana/los-haitises-national-park-2/" target="_blank" >
                <img class="DestinationsPic" src="https://icorridor.org/storymaps/wp-content/uploads/2018/04/los-haitises-national-park-the-crown-jewel-of-samana-bay-in-the-dominican-republic.jpg"
                alt="Los Haitises" > </a>
                <footer class="footerPic">Los Haitises, National Park</footer>
           </div> 
                   
           
             
              
        </div>
        <br><br>

        <footer id="footer"> Made by: <a class="link" href="https://www.linkedin.com/in/brayanmnz/" target="_blank" >@BrayanMnz</a> <br></footer>
    </body>




</html>
