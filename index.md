
<html lang="es">
<head>
	<title>Mi primera página</title>
	<meta charset="utf-8">
</head>
<body bgcolor="#5522AA" text="FFFFFF" link="BBBBBB" vlink="111111">
<!--
   <body background="/home/luis/Imágenes/wallpapers/wallhaven-mpw5qk.png"> 
--> 
    <a name="encabezado"></a>
	<h1><center>Primera página</center></h1>
	
	<hr>
	Esta es mi primera pagina, aunque solo sea un texto. Como el lenguaje HTML no es dificil,pronto estare en condiciones de hacer cosas interesantes.
	<p>Y aquí un segundo parrafo. :P</p>
	<hr align="center" size="10" width="80%" noshade color="#ffdfff">
	<pre>
		    Un truen lejano
		    un cielo nublado.
		    En caso de que llueva
		    ¿te quedaras a mi lado?
		    ...
	</pre>
	<hr noshade align="center" size="10" width="80%" color="#ffafff">
	<tt>
		    Un truen lejano
		    un cielo nublado.
		    En caso de que llueva
		    ¿te quedaras a mi lado?
		    ...
	</tt>
	<hr noshade align="center" size="10" width="80%" color="#ff7fff">
	<p>
		Cuando aparace un simbolo <sup>2</sup> como este<br>
		significa que se trata de un superindice.<br>
		<br>
        Cuando aparace un simbolo <sub>2</sub> como este<br>
		significa que se trata de un subindice.<br>

	</p>
	<A HREF="mailto: luisserapiomartinez@gmail.com"> Instituto Galego de Formación</A>
	<!-- Esto es un comentario :P -->
	<hr nochade align="center" size="5" width="100%" color="#ff4fff">
	<a name="listas_ol"></a>
	<h2>Listas ordenadas con etiqueta ol -> ordered list </h2>
	<ol type="1">
		<li>Uno</li>
		<li>Dos</li>
		<li>Tres</li>
	</ol>

	<ol type="a">
		<li>Uno</li>
		<li>Dos</li>
		<li>Tres</li>
	</ol>
	<ol type="I">
		<li>Uno</li>
		<li>Dos</li>
		<li>Tres</li>
	</ol>
	<hr nochade align="center" size="5" width="100%" color="#ff4fff">
	<a name="listas_ul"></a>
	<h2>Listas no ordenadas con etiquete ul -> unorder </h2>
	<ul type="square">
		<li>Uno</li>
		<li>Dos</li>
		<li>Tres</li>
	</ul>
	<ul type="circle">
		<li>Uno</li>
		<li>Dos</li>
		<li>Tres</li>
	</ul>
	<ul>
		<li>Uno</li>
		<li>Dos</li>
		<li>Tres</li>
	</ul>
	<hr nochade align="center" size="5" width="100%" color="#ff4fff">
	<a name="enlaces"></a>
	<h2>Enlaces.</h2>
	<h3>Dentro de la misma página.</h3>
	<a href="#encabezado">Enlace al encabezado de la página.</a>
	<h3>Con otra página nuestra.</h3>
	<a href="Estructura_del_cuerpo.html">Otra pagina de mi pertenencia</a>
	<h3>Fuera de nuestro sistema</h3>
	<a href="http://google.com">google</a>
	<h2>Imágenes.</h2>
	Esta imagen es de AmongUs -> <a href="#encabezado"><img src="among_us_icon_156743.png" align="middle" border="2" width="50" height="50"></a><- que tambien es un enlace.

	<hr nochade align="center" size="5" width="100%" color="#ff4fff">
	<a name="tablas"></a>
	<h2>Tablas</h2>
	<table border="5" width="100%">

		<tr>
			<td>11</td>
			<td>12</td>
			<td>13</td>
			<td>14</td>
		</tr>
		<tr>
			<td>21</td>
			<td>22</td>
			<td>23</td>
			<td>24</td>
		</tr>
		<tr>
			<td>31</td>
			<td>32</td>
			<td>33</td>
		</tr>
		<tr>
			<th>41</th>
		</tr>
		<tr>
			<td align="right">Esta es una celda.</td>
			<td align="left">Y esta es otra celda.</td>
			<td align="center"><img src="among_us_icon_156743.png" align="middle" border="2" width="100" height="100"></td>
			<td valign="middle" align="middle">Otra celda más.</td>
		</tr>
		<tr>
			<td>
				<table border="10" align="center" width="80%">
					<tr>
						<td>1</td>
						<td>2</td>
					</tr>
					<tr>
						<td>3</td>
						<td>4</td>
					</tr>
					<caption>Matriz con grosor 10</caption>
				</table>
			</td>
			<td colspan="2" align="center">Otra celda más!</td>
			<td rowspan="2" valign="center">Maaaas!</td>
		</tr>
		<tr>
			<td>
				<table bgcolor="#226622" border="5" width="80%" align="center">
					<tr>
						<td bgcolor="#000000">1</td>
						<td>2</td>
					</tr>
					<tr>
						<td>3</td>
						<td>4</td>
					</tr>
					<caption>Tabla con color de fondo</caption>
				</table>
			</td>
			<td>
				<table background="wallhaven-mpw5qk.png" border="5" width="80%" align="center">
					<tr>
						<td>1</td>
						<td>2</td>
					</tr>
					<tr>
						<td>3</td>
						<td>4</td>
					</tr>
					<caption>Tabla con imagen de fondo</caption>
				</table>
			</td>
			<td align="center">
				<table border="5" cellspacing="20">
					<tr>
						<td>1</td>
						<td>2</td>
					</tr>
					<tr>
						<td>3</td>
						<td>4</td>
					</tr>
					<caption>Cellspacing</caption>					
				</table>
				<table cellpadding="20">
					<tr>
						<td>1</td>
						<td>2</td>
					</tr>
					<tr>
						<td>3</td>
						<td>4</td>
					</tr>
					<caption>Cellpadding</caption>					
				</table>
			</td>
		</tr>
		<caption>Matriz con grosor 5</caption>

	</table>
	<hr nochade align="center" size="5" width="100%" color="#ff4fff">
	<a name="formularios"></a>
	<h2>
		Formularios.
	</h2>
	<center>
	<form action="mailto:luisserapiomartinez@gmail.com" method="post" enctype="text/plain">
		Nombre de usuario:
		<br><input type="text" name="usuario"><br>
		Contraseña:
		<br><input type="password" name="contraseña"><br>
		Pais de origen:
		<br><select name="pais">
			<option>México</option>
			<option>Argentina</option>
			<option>Brasil</option>
			<option>Honduras</option>
			<option>USA</option>
		</select><br>
		<input type="radio" name="opcion_color" value="rojo">Rojo <br>
		<input type="radio" name="opcion_color" value="azul">Azul <br>
		<input type="radio" name="opcion_color" value="verde">Verde <br>
		<small>Acepto el uso de mis datos para...</small>
		<input type="checkbox" name="condiciones" ><br>
		<input type="submit" value="Enviar" > <input type="reset" value="Borrar">
	</form>
	</center>
	<p>
		<center>
			<H2>Libro de visitas</H2>
			<FORM ACTION="mailto:luisserapiomartinez@gmail.com" METHOD="POST" ENCTYPE="TEXT/PLAIN">
				Tu nombre:
				<BR><INPUT TYPE="text" NAME="Nombre">
				<BR>Escribe tus comentarios:
				<BR><TEXTAREA NAME="Comentarios" ROWS="6" COLS="40"></TEXTAREA>
				<BR><INPUT TYPE="submit" VALUE="Enviar datos">
				<INPUT TYPE="reset" VALUE="Borrar datos">

			</FORM>
		</center>
	</p>
	<hr nochade align="center" size="5" width="100%" color="#ff4fff">
	<a name="mapas"></a>
	<h2>Mapas</h2>
	<map name="mi_mapa">
		<area shape="rect" coords="0,0,50,50" href="Estructura_del_cuerpo.html">
		<area shape="circle" coords="100,100,40" href="http://google.com" target="_blank">
		<area shape="default" nohref>
	</map>
	<center>
		<img src="wallhaven-mpw5qk.png" width="200" height="200" usemap="#mi_mapa">
		<figcaption>Imagen mapeada</figcaption>
	</center>
    <h2>Sonidos</h2>
    <audio src="The Doors   Ghost Song (1080 HD).mp3" controls>
    	<track kind="subtitles" src="/sub-en.vtt" srclang="en" label="English" default>
    </audio>
    <br>
    <video controls width="40%" height="40%">
    	<source src="Scorpions_Still_Loving_You_-_Gabriella_Quevedo(youtube.com).mp4">
    	<track src="sub-en.vtt" lang="en" label="English" default>
    </video>
    
</body>
</html>

