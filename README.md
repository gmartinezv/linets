german.linets  0.1.0
=============

Demo Desafio Latam LINETS.

<b><a href="http://martinezweb.com.ve/linets/" target="blank">Demo</a></b> | <b><a href="https://github.com/gmartinezv/README.md#options">Documentación</a></b>

Uso
-------
__Styles:__

Incluye las librerias de Bootstrap 3 y less/animated.css
~~~~ html
<link href="less/estilo.less" type="text/css" rel="stylesheet" />
~~~~
__Javascript:__

Incluye las librerias de JQuery 1.12.4., less.min.js y wow.min.js
~~~~ html
<script src="less/principal.js"></script>
 
~~~~

Con el uso de las librerias se optimiza el codigo, contiene un diseño animado, alegre y limpio. Contiene una funcion de CambiodeFondo en el que se cambia el fondo de la imagen principal por las siguientes imagenes que vinieron incorporada. 

~~~ javascript

var CambiarFondo = function(){
      if (fondo_actual == fondos.length) {
           fondo_actual = 0;
         }
        var precargar =fondo_actual; 
        var precargar2 = fondo_actual++;
         
        $('#hero-area').css('background-image', 'url(imagen/'+fondos[precargar]+')');
         
        $('#precargar').css('background-image',  'url('+fondos[precargar2]+ ')');

  }
~~~~

Options
-------
* __comienza aca__  boton que despliega una ventana tipo modal utilizando JQuery y las librarias de Bootstrap.
* __Mas Info__ al igual que el anterior, este boton usa la misma ventana pero con contenido y efecto diferente.
* __Equipo__ al bajar en el contenido o precionar el boton de "equipo" el contenido de texto e imagen tiene animación.
* __Blog__ el boton de inscribete tiene otra animación distinta de las anteriores.
* __contacto__ aqui podemos notar y en todas las sessiones de la pagina el contenido de "responsive" ya que se adapta a cualquier pantalla de cualquier dispositivo.
* __Footer o Pie__ incluida la información solicitada y adicional la imagen restante.
 

License
-------
> Licensed under <a href="http://opensource.org/licenses/MIT">MIT license</a>.
