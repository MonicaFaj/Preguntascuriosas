<!DOCTYPE html>
<html lang="es">
<head>
	<tittle>Preguntas curiosas</tittle>
	<meta charset="UTF-8">
	<link rel="stylesheet" href="css/bootstrap.min.css">
	<!--Estilos-->
	<style>
	.jumbotron{
		background-color: #808080 ;
		color: #ffffff;
		padding: 100px 25px;
		font-family: sans-serif;
		text-align: center;
	}
	.container-fluid {
		padding: 40px 50px;
	}
	.bg-grey {
		background-color: #DCDCDC;
	}
	</style>
</head>
<body>
	<header>
		<div class="jumbotron">
		<h1>Preguntas curiosas</h1>
		<form>
			<input type="text" size="100" placeholder="Tu pregunta curiosa">
			<button type="button">Buscar</button>
		</form>
	</div>
	</header>
	<!--Sección Acerca de-->
	<section class="container-fluid">
		<!DOCTYPE html>
<html>
<body>
	<div class="center">
    <img src="milogo.png" alt="LOGO" width="300" height="200">
</body>
</html>
		<h2>Acerca de nosotros</h2>
		<h4>Somos una asociacón encargada de ofrecerte un servicio el cual consiste en que cada una de tus preguntas sean respondidas de la mejor forma, siendo claras y de fuentes confiables.</h4>
		 <a href="Mas informacion.html" class="btn btn-primary btn-lg">Más Información</a>
</section>
	<!--Sección Nuestros valores-->
	<section id="contacto" class="container-fluid bg-grey">
        <h2 class="text-center">Objetivos</h2>
        <div class="row">
            <div class="col-sm-5">
		<h2>Nuestros objetivos</h2>
		<p><strong>1-</strong> Satisfacer las necesidades de nuestros clientes, creando un ambiente correcto y cuidando de la privacidad del usuario. </p>
		<p><strong>2-</strong> Satisfacer las necesidades de nuestros usuarios.</p>
		<p><strong>3-</strong> Manter siempre el compromiso, honestidad, innovación y respeto a nuestros usuarios</p> <br>
	</section>
	<!DOCTYPE html>
<html>
<head>
    <title>Pagina principal</title>
</head>
<body>
<header>
		<h3> Inicia con nosotros</h3> 
		<br>
<button onclick="myFunction()">Iniciar sesión</button>

<script>
function myFunction() {
  window.location.href = "file:///C:/Users/MINEDUCYT/Desktop/Tbox%20Proy/Preguntas%20Curiosas.html"; // Aquí se debe colocar la URL de la página a la que se desea redirigir
}
</script>
<!--Sección de Contacto-->
    <section id="contacto" class="container-fluid bg-grey">
        <h2 class="text-center">CONTACTO</h2>
        <div class="row">
            <div class="col-sm-5">
                <h4>Información de contacto</h4>
                <p><span class="glyphicon glyphicon-envelope"></span>Col. Galdavez #43</p>
                <p><span class="glyphicon glyphicon-plus"></span>0000-0333</p>
                <p><span class="glyphicon glyphicon-cloud"></span>preguntascuriosas@gmail.com</p>
            </div>
            <div class="col-sm-7">
            <form>
                <div class="row">
                    <div class="col-sm-6 form-group">
                        <input class="form-control" name="name" placeholder="Nombre" type="text" required>
                    </div>
                    <div class="col-sm-6 form-group">
                        <input class="form-control" name="email" placeholder="Usuario" type="text" required>
                    </div>
                </div>
                <textarea class="form-control" name="pregunta" placeholder="Pregunta" rows="4"></textarea><br>
                <div class="row">
                    <div class="col-sm-12 form-group">
                        <button class="btn btn-default pull-right" type="submit">Enviar</button>
                    </div>
                </div>
            </form>               
            </div>
        </div>
    </section>
   <!--Sección Mapas-->
    <section class="container-fluid">
        <h3>Nuestra ubicación</h3>
        <div class="row">
            <div class="col-sm-12">
                <!-- Asignar alto y ancho con CSS -->
<div id="googleMap" style="height:300px;width:90%;"></div>
<!-- Agregar Google Maps -->
<script src="http://maps.googleapis.com/maps/api/js"></script>
<script>
var myCenter = new google.maps.LatLng(13.461627, -88.168227);
function initialize() {
var mapProp = {
center:myCenter,
zoom:15,
scrollwheel:true,
draggable:true,
mapTypeId:google.maps.MapTypeId.ROADMAP
};
var map = new google.maps.Map(document.getElementById("googleMap"),mapProp);
var marker = new google.maps.Marker({
position:myCenter,
});
marker.setMap(map);
}
google.maps.event.addDomListener(window, 'load', initialize);
</script>

            </div>
        </div>
    </section>
    <!--Pie de página-->
<footer class="container-fluid text-center">
	<a href="#inicio" title="Ir al inicio">
		<span class="glyphicon glyphicon-home"></span>
	</a>
<p>Página creada por: <a href="#inicio" title="Visite nuestro sitio">www.preguntascriosas.com</a></p> 
</footer>

    <!--Script para añadir desplazamiento suave-->
<script>
    $(document).ready(function(){
      // Agrega desplazamiento suave a anclas en barra de navegación y pie.
      $(".navbar a, footer a[href='#myPage']").on('click', function(event) {
      // Removiendo comportamiento por defecto.
      event.preventDefault();
      // Almacenando el contenedor destino.
      var hash = this.hash;
      // Agregando desplazamiento suave.
      // El 900 son los milisegundos para moverse.
      $('html, body').animate({
     // Moviendo sitio a contenedor destino.
        scrollTop: $(hash).offset().top
      }, 900, function(){
        // Añade el ancla a la dirección.
        window.location.hash = hash;
        });
      });
    })
    </script>
    
</body>
</html>
</body>
</html>
