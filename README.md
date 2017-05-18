<!doctype html>
<html>
    <head>
        <meta charset="utf-8">
        <link rel="stylesheet" type="text/css" href="estiloPortfolio.css">
        <script src="Preview.js"></script>
        <title>Portfolio</title>
    </head>
    
    <body>
        <div class="header">
            <div class="logoNav"></div>
        </div>
        <div class="article">

           	<div id="Media" class="tabcontent">
              <h3>Media</h3>
            	<div class="articleVisor">
        
                    <div id="imagen1" class="tabcontentVisor">
                      <img src="source/jim.jpg" alt="skate">
                    </div>
                    
                    <div id="imagen2" class="tabcontentVisor">
                      <img src="source/jim.jpg" alt="skate">
                    </div>
                    
                    <div id="imagen3" class="tabcontentVisor">
                      <img src="source/jim.jpg" alt="skate">
                    </div>
                    
                    <div id="imagen4" class="tabcontentVisor">
                     <img src="source/jim.jpg" alt="skate">
                    </div>
                    
                    <div class="visorImg">
                      <button class="tablinks" onclick="openImg(event, 'imagen1')"><img class="littleimg" src="source/littleJim.jpg"></button>
                      <button class="tablinks" onclick="openImg(event, 'imagen2')">Imagen 2</button>
                      <button class="tablinks" onclick="openImg(event, 'imagen3')">Imagen 3</button>
                      <button class="tablinks" onclick="openImg(event, 'imagen4')">Imagen 4</button>
                    </div>
                </div>
            </div>
            
            <div id="Inicio" class="tabcontent">
              <h3>Inicio</h3>
              <p>wqaezsdkj</p> 
            </div>
            
            <div id="Sobre Mi" class="tabcontent">
              <h3>Sobre Mi</h3>
              <p>Pues es......................to deberia ser una explicacion pe...............ro no he tenido tiempo.</p> 
            </div>
            
            <div id="Contacto" class="tabcontent">
              <h3>Contacto</h3>
              <p>UUUUUUUUHHHHH JAAAAAHH.</p>
            </div>
          
            <div class="tab">
            	<button class="tablinks" onclick="openCity(event, 'Inicio')">Inicio</button>
            	<button class="tablinks" onclick="openCity(event, 'Sobre Mi')">Acabados</button>
            	<button class="tablinks" onclick="openCity(event, 'Contacto')">Contacto</button>
            	<button class="tablinks" onclick="openCity(event, 'Media')">Media</button>
            </div>
        </div>
        <div class="footer"></div>
    </body>
</html>
