# Project OP Code

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="style.css">
    <script src="javascript.js"></script>
    <title>Project OP</title>
</head>

<header>
    
    <h1>Word jij een mediadeveloper?</h1>
   
</header>

<body>
    
    <section>
            <nav>
                
                    <ul>
                        <li>
                            <a href="#">Home</a>
                        </li>
               
                        <li>
                            <a href="#opleiding">Opleiding</a>
                        </li>
               
                        <li>
                            <a href="#mediacollege">Mediacollege</a>
                        </li>
               
                        <li>
                            <a href="#filmpje">Filmpje</a>
                        </li>

                        <li>
                                <a href="#contact">Contact</a>
                            </li>
               
                        <li>
                            <a href="#inschrijven">Schrijf je in!</a>
                        </li>

                        
                    </ul>
                </nav>
                <h1 class="Inleiding">Inleiding</h1>
        <p>Welkom op deze website. Hier kan je de informatie over de opleiding Mediadeveloper vinden. Je vind hier ook informatie over het Mediacollege zelf. Er is ook een filmpje waar de een paar leerlingen vertellen over hun eigen ervaring met het Mediacollege. Als je je wilt inschrijven voor een opendag kan je dat ook meteen doen op deze website.</p>
    </section>

    

    <section class="section1" id="opleiding">
        <h2>Informatie over de opleiding</h2>
        <p>De opleiding Mediadeveloper is een niveau 4 opleiding met een duur van 3 jaar. In die 3 jaar zal je leren werken met verschillende soorten programma's om mooie websites, apps en webapplicaties in elkaar te kunnen zetten. 
            Als Mediadeveloper zal je leren hoe je websites, apps en webapplicaties kan bouwen en onderhouden. 
            Je zal niet alleen leren programmeren maar ook hoe je een mooie website kan maken op basis van vormgeving. 
            Je leert ook samenwerken met Mediavormgevers, die zullen uiteindelijk de vormgeving van je website, app of webapplicatie bepalen.
            Voor deze opleiding heb je geen vooropleiding nodig. De mogelijkheden na deze opleiding zijn wel groot. Je kan je ergens in gaan specialiseren of een HBO doen</p>
            <img src="code_scherm.jpg" alt="codescherm" class="image">
        

    </section>
    
    

    <section class="section2" id="mediacollege">
            <h2 class="media">Mediacollege</h2>
            <p>Het Mediacollege Amsterdam is een school met een veilige en gezellige sfeer. Je hebt een ruime keuze uit opleidingen en de docenten zijn grotendeels wel chill.
               Het Mediacollege is een school die er alles aan doet om studenten te laten slagen en ze verder te helpen met hun toekomst.
               Ze laten vaak bedrijven langskomen voor lezingen en er zijn veel leuke opdrachten waar je leert samen te werken met mensen uit een andere opleiding en met bedrijven.
               Het Mediacollege zorgt er al ruim 100 jaar voor dat studenten slagen voor hun opleiding en verder kunnen werken aan hun toekomst. 
            </p>
            <img src="mediacollege2.jpg" alt="mediacollege" class="image">

    </section>

    

    <section class ="section3" id="filmpje">
        <h2 class="h2filmpje">Filmpje</h2>
        <p>Hier is een filmpje gemaakt door studenten op het Mediacollege. Ze hebben het over wat ze leuk vinden over deze school.
            In dit filmpje praten alleen studenten van de opleiding Mediadeveloper.
        </p>
        <video width="400" controls>
            <source src="schoolpromotie.mp4" type="video/mp4"></video>
        

    </section>
    

    <section class="section5" id="contact">
        <h2 class="h2contact">Contact</h2>
        <p>Heeft u nog vragen of is iets nog niet helemaal duidelijk, contacteer ons dan.</p>
         <p class="p1"><span>&#128231;</span>Mail: info@ma-web.nl</p>
         <p class="p1"><span>&#128241;</span>Telefoonnummer: 020 850 95 00</p>
         <p class="p1"><span>&#11162;</span>Plaats: contactweg 36 1014 AN Amsterdam</p>
         <p class="p1"><span>&#8252;</span>Kom naar de open dag op 22 januari!</p> 
         
        
        

    </section>

    
    <footer class="footer" id="inschrijven">
        <h2 class="h2inschrijven">Schrijf je in!</h2>
        <fieldset>
            <form action="http://bla.hosts.ma-cloud.nl/pop.php" method="get">
           
                <input type="text" name="Naam" value="Naam">
           <br>
           <input type="text" name="Email" value="Email">
           <br>
            <select name="Leeftijd">
                <option value="">Kies je leeftijd</option>
                <option value="14">14</option>
                <option value="15">15</option>
                <option value="16">16</option>
                <option value="17">17</option>
                <option value="18">18</option>
                <option value="19">19</option>
                <option value="20">20</option>
                <option value="21+">21+</option>
                <br>
                <input type="submit" value="Versturen">
                
                </select>
            </form>
            <div id="validatie">
                <a href="http://validator.w3.org/check?uri=referer" target="_blank">
                    <img src="http://blog.boyet.com/blog/files/media/image/valid-html5-blue.png" alt="Valide HTML5"></a>
                <a href="http://jigsaw.w3.org/css-validator/check/referer" target="_blank">
                    <img src="http://jigsaw.w3.org/css-validator/images/vcss-blue.gif" alt="Valide CSS">
                </a>
            </div>
        </fieldset>
    </footer>
</body>
</html>

#CSS

*{
    scroll-behavior: smooth;
    padding: 0%;
    margin: 0%;
    box-sizing: border-box;
}

html{
    background-color: #f11890;
}


section{
    width: 100%;
    height: 800px;
    background-color: black;
   
    
}

h1{
    padding-left: 35%;
    padding-top: 4%;
    color: white;
    background-color: black;
}



header{
    background-image: url(MA.jpg);
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: cover;
    padding-bottom: 50%;
    height: 100%;
}

.section1{
    background-color:  rgb(22, 22, 22);
}

.section2{
    background-color: black;
}

.section3{
    background-color:  rgb(22, 22, 22);
}

.footer{
    background-color:  rgb(22, 22, 22);
    height: 450px;
}

.section5{
    background-color:  rgb(0, 0, 0);
}

ul{
    display:flex;
    background-color:  rgb(0, 0, 0);
    
}

li{
    padding: 1%;
    padding-left: 9%;
    
}

nav a {
color: #f11890;
    text-decoration: none;
    background-color: rgb(0, 0, 0);
    font-weight: 700;
    border-bottom: 5px solid transparent;
    flex: 1;
}

nav a:hover {
    color: #f11890;
    background: #807c90;
    flex: 1;
 }

 .Inleiding{
     padding-left: 48%;
     
 }

 h2{
     color: white;
     padding-left: 40%;
     

 }

 p{
     color: white;
     text-align: center;
     padding-left: 20%;
     padding-right: 20%;
     padding-top: 5%;
     padding-bottom: 2%;
 }

 .image{
     width: 99%;
     height: 65%;
     padding-left: 1%;

 }

 .media{
     padding-left: 45%;
     padding-top: 2%;
 }

 .h2filmpje{
     padding-left: 47%;
     padding-top: 2%;
 }

 .h2contact{
     padding-left: 47%;
     padding-top: 2%;
 }

 .h2inschrijven{
     padding-left: 45%;
     padding-top: 2%;
 }

 h2{
     padding-top: 2%;
 }

 span {
     content: \01F4F1;
    content: \00203C; 
    content: \01F4E7;
    content: "\2B9A";
    content: "\1F4F1";
    font-size: 48px;
    color: #f11890;
    
}

.p1{
     color: white;
     text-align: center;
     padding-left: 20%;
     padding-right: 20%;
     padding-top: 1%;

}
fieldset{
    padding-bottom: 10%;
    padding-top: 3%;
    height: 385px;
}

label{
    padding-top: 3%;
}

select{
    margin-left: 45%;
    margin-top: 2%;
    padding: 1%;
}

input{
    margin-left: 45%;
    margin-top: 2%;
    padding: 1%;
}

#validatie img {
    height: 1em;
    width: auto;
    border: 0;
    margin: 0 .3em;
    
}

footer{
    height: 400px;
}

video{
    margin-left: 37%;
}







 
 

