# «montajescuadriculados»

Unos comandos de bash con algunos parámetros para obtener una clase específica de montajes. Usa imagemagick entonces hay que tenerlo instalado, luego todo se hace con la función montage. 

> bash '/home/azul/montajescuadriculados/montajescuadriculados.sh' 450 webp mimontaje_ %F

Es importante poner los siguientes parámetros, lo de arriba es el ejemplo. En la salida...
- 450: Cada imagen será de 450x450px.
- webp: La imagen resultante tendrá formato webp.
- mimontaje_: El archivo tendrá primero la fecha y segundo el sufijo mimontaje_.
- %F: Cada imagen a incluir en la salida.

De no tener imagemagick, descargar: https://imagemagick.org/script/download.php#linux
