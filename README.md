<!doctype html>
<html lang="pl-pl">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.5.0/font/bootstrap-icons.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
  
    <style>
      .teks2{
        border-style: solid;
      }

.pomocy{
    width: 100%;
    top: 100px;
    right: 0px;
    height: 745px;
}

.slides{
    position: absolute;
    width: 100%;
    top: 100px;
    right: 0px;
    height: 745px;
}

#o1, #o2, #dine-image, #watch-image{
    position: absolute;
}
    </style>

<script>
  var i = 0;
  var czasAnimacji;
  function animate(){
          if(i == 0){
              $( "#o1" ).fadeOut( 1500 )
              $( "#o2" ).fadeIn( 1500 );
          }
          else if(i == 1){
              $( "#o2" ).fadeOut( 1500 )
              $( "#o3" ).fadeIn( 1500 );
          }
          else if(i == 2){
              $( "#o3" ).fadeOut( 1500 );
              $( "#o4" ).fadeIn( 1500 );
          }
          else if(i == 3){
              $( "#o4" ).fadeOut( 1500 )
              $( "#o1" ).fadeIn( 1500 );
          }
  
          if(i == 3) i = 0;
          else i++;
  };  
      function StartSlider(){
      czasAnimacji = setInterval(animate, 4000);
      animate(); 
      }
     
  
      function StopSlider(){
          clearInterval(czasAnimacji);
      }
      
      
  </script>
  </head>
  <body>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>

    <div class="Logo bg-dark" style="height: 100px; text-align: center; color: white; font-size: 40px; padding-top: 15px;">Art of Graphics</div>

    <!--slider-->

     <div class="pomocy">
        <img id="o1" onmouseover="StopSlider()" onmouseout="StartSlider()" class="slides" src="slider.png" />
        <img id="o2" onmouseover="StopSlider()" onmouseout="StartSlider()" class="slides" src="slider.png"/>
        <img id="o3" onmouseover="StopSlider()" onmouseout="StartSlider()" class="slides" src="slider.png"/>
        <img id="o4" onmouseover="StopSlider()" onmouseout="StartSlider()" class="slides" src="slider.png"/>
    </div>

    <!--navbar-->

    <nav class="nav nav-pills flex-column flex-sm-row bg-dark" style="color: white; height: 100px;">
      <a class="flex-sm-fill text-sm-center nav-link " aria-current="page" href="STRONA GOTOWA DO OCENY.html" style="font-size: 30px; padding-top: 25px; color: white !important;"><i class="bi bi-house-fill"></i> Strona główna</a>
      <a class="flex-sm-fill text-sm-center nav-link " aria-current="page" href="kategoria.html" style="font-size: 30px; padding-top: 25px; color: white !important;"><i class="bi bi-bag-fill"></i> Produkty</a>
      <a class="flex-sm-fill text-sm-center nav-link " aria-current="page" href="onas.html" style="font-size: 30px; padding-top: 25px; color: white !important;"> <i class="bi bi-file-person-fill"></i> O nas</a>
      <a class="flex-sm-fill text-sm-center nav-link " aria-current="page" href="logowanie.html" style="font-size: 30px; padding-top: 25px; color: white !important;"> <i class="bi bi-door-open-fill"></i> Logowanie</a>
    </nav>

    <!--teks1 i obrazek1-->
    <div class = "row">
      <div class = "tekst col-lg-6" style="font-size: large; margin: auto; border-style:groove; border-radius: 25px; padding-top: 40px; background-color: gray; color: white;">
      Lorem Ipsum jest tekstem stosowanym jako przykładowy wypełniacz w przemyśle poligraficznym. Został po raz pierwszy użyty w XV w. przez nieznanego drukarza do wypełnienia tekstem próbnej książki. Pięć wieków później zaczął być używany przemyśle elektronicznym, pozostając praktycznie niezmienionym. Spopularyzował się w latach 60. XX w. wraz z publikacją arkuszy Letrasetu, zawierających fragmenty Lorem Ipsum, a ostatnio z zawierającym różne wersje Lorem Ipsum oprogramowaniem przeznaczonym do realizacji druków na komputerach osobistych, jak Aldus PageMaker
      <div class = "row">
        <div class = "tekst" style="font-size: large; margin-top: 60px; text-align: center;">
          <i>"We are the architects of our own soul. We destroy, we build, and our most important tool is art. This is our way of expressing ourselves and showing who we really are." ~ Art of Graphics</i>
        </div>
      </div>
    </div>
      <div class=" obrazek col-lg-5" style="justify-content: center; text-align: center;">
    <img src="logo.png" style="width: 500px; height: 500px;">
      </div>
    </div>
   
    <!-- polecane produkty -->
  <div class = "pasek1 bg-dark">
    <div class="polecako" style="font-size: 30px; padding-top: 25px; color: white !important; text-align: center;">Również Polecamy!</div>
    <div class="row">
    <div class="card col-lg-3" style="width: 18rem; margin: auto;">
      <img src="abstrakcja 1.jfif" class="card-img-top" alt="...">
      <div class="card-body">
        <p class="card-text" style="text-align: center;"><div class="cos" style="font-size: large; padding-bottom: 10px;"><i>Morska abstrakcja</i></div>Vestibulum scelerisque malesuada diam vitae vestibulum. Nulla facilisis pellentesque ipsum vel feugiat. Morbi est lacus, maximus ac eros eget, aliquam... <div class="br"><a href="podstrona produkt.html">Czytaj dalej</a></div></p>
      </div>
    </div>
    <div class="card col-lg-3" style="width: 18rem; margin: auto;">
      <img src="tak.jpg" class="card-img-top" alt="...">
      <div class="card-body">
        <p class="card-text" style="text-align: center;"><div class="cos" style="font-size: large; padding-bottom: 10px;"><i>Zachmurzone niebo</i></div>Vestibulum scelerisque malesuada diam vitae vestibulum. Nulla facilisis pellentesque ipsum vel feugiat. Morbi est lacus, maximus ac eros eget, aliquam... <div class="br"><a href="podstrona produkt 3.html">Czytaj dalej</a></div></p>
      </div>
    </div>
    <div class="card col-lg-3" style="width: 18rem; margin: auto;">
      <img src="abstrakcja-90x90-4.png" class="card-img-top" alt="..."  style="width: 262px; height: 262px;">
      <div class="card-body">
        <p class="card-text" style="text-align: center;"><div class="cos" style="font-size: large; padding-bottom: 10px;"><i>Erupcja wulkanu</i></div>Vestibulum scelerisque malesuada diam vitae vestibulum. Nulla facilisis pellentesque ipsum vel feugiat. Morbi est lacus, maximus ac eros eget, aliquam... <div class="br"><a href="podstrona produkt 2.html">Czytaj dalej</a></div></p>
      </div>
    </div>
    <div class="card col-lg-3" style="width: 18rem; margin: auto; padding: auto; margin-bottom: 50px;">
      <img src="abstrakcja 1.jfif" class="card-img-top" alt="...">
      <div class="card-body">
        <p class="card-text" style="text-align: center;"><div class="cos" style="font-size: large; padding-bottom: 10px;"><i>Morska abstrakcja</i></div>Vestibulum scelerisque malesuada diam vitae vestibulum. Nulla facilisis pellentesque ipsum vel feugiat. Morbi est lacus, maximus ac eros eget, aliquam... <div class="br"><a href="podstrona produkt 4.html">Czytaj dalej</a></div></p>
      </div>
    </div></div></div></div>

  <!-- newsletter -->
<div class="row">
  <div class = "newsletter col-lg-6" style="height: 100px; text-align: center; margin-top: 50px; margin-left: 40px;">
    <label for="exampleFormControlInput1" class="form-label">Email address</label>
  <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
</div>
<div class="teks13 col-lg-5" style="height: 100px; text-align: center; margin-top: 60px; margin-bottom: 40px;"> Zapisz się do naszego newslettera już dzisiaj! Darmowa subskrybcja oferuje wcześniejsze powiadomienia o aktualnie trwających promocjach, pomaga zaznajomić się klientowi ze szczegółami innych ofert na naszej stronie i wiele wiele innych! Z subskrybcji można w każdej chwili zrezygnować.</div>
  </div>
 
 <!--stopka-->
 
  <div class = "pasek bg-dark " style="height: 250px; color: white; font-size: 30px; text-align: center;">
    <div class="row">
    <div class = "opcje2 col-lg-3" style="padding-top: 30px;">Kontakt
      <div class = "lista1 " style="text-align: center !important; font-size: 20px !important; padding-top: 20px; margin:auto !important;">
        <ul>
          <li>Numer telefonu: 123456789</li>
          <li>E-mail: firma@gmail.com</li>
          <li>Fax 32 134 13 95</li>
        </ul>
      </div></div>
    <div class = "opcje3 col-lg-3" style="padding-top: 30px;">Informacje
    <div class = "lista2 " style="text-align: center !important; font-size: 20px !important; padding-top: 20px; margin:auto;">
    <ul>
          <li>Numer telefonu: 123456789</li>
          <li>E-mail: firma@gmail.com</li>
          <li>Fax 32 134 13 95</li>
        </ul>
      </div></div>
    <div class = "opcje4 col-lg-3" style="padding-top: 30px;">Obsługa klienta
    <div class = "lista3 " style="text-align: center !important; font-size: 20px !important; padding-top: 20px; margin:auto;">
    <ul>
          <li>Numer telefonu: 123456789</li>
          <li>E-mail: firma@gmail.com</li>
          <li>Fax 32 134 13 95</li>
        </ul>
      </div></div>
    <div class = "opcje5 col-lg-3" style="padding-top: 30px;">Twoje konto
    <div class = "lista4 " style="text-align: center !important; font-size: 20px !important; padding-top: 20px; margin:auto;">
    <ul>
          <li>Numer telefonu: 123456789</li>
          <li>E-mail: firma@gmail.com</li>
          <li>Fax 32 134 13 95</li>
        </ul>
      </div></div>
  </div>
</div>
  </body>
</html>
