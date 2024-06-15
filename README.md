# Breve guía sobre NEOVIM

Vamos a repasar tres modos básicos que tenemos con VIM. Modo inserción de datos, modo normal y visual (selección).

Por defecto estamos en modo normal.

*** GIF 1

![Modo normal](/img/01.gif)

y pulsando la tecla "i" entramos en modo inserción.

*** GIF 2

![Modo normal](/img/02.gif)

Con la tecla "ESC", saldremos del modo inserción y volveremos al modo de visualización.

Hay diversas maneras de moverse o acciones pero aquí vamos a revisar sólo algunas que nos parecen aconsejables para 
empezar a usar VIM, en nuestro caso a través de NEOVIM.

*** GIF 3

![Modo normal](/img/03.gif)

Para ir al inicio y final de una fila podemos hacer uso de la tecla "INICIO" o del número "0". PAra ir al final podemos
haceer uso de la tecla "FIN" o de la tecla "$".

*** GIF 4

![Modo normal](/img/04.gif)

Con la tecla "*" encontramos la siguiente palabra que sea igual a la indicada por la posición del cursos. 

*** GIF 5

![Modo normal](/img/05.gif)

Con la tecla "#", se buscará la anterior. El movimiento será el mismo pero hacia atrás.

Con la tecla "CTRL+INICIO" o "gg" se irá al inicio del fichero y con la tecla "CTRL+FIN" o "G" irá al final del fichero.


Para mostrar el número de filas podemos hacer uso de ":set nu". Para quitarlas, ":set nonu". 
Se puede configurar el fichero de configuración para cambiar el modo de funcionamiento por defecto.


*** GIF 6

![Modo normal](/img/06.gif)


Para ir a una fila concreta, se puede usar la tecla "G" precedida del número de fila. Ejemplo "2G" para ir a la 2da fila.

*** GIF 7

![Modo normal](/img/07.gif)

En texto donde se use paréntesis o llaves, con el símbolo % de porcentaje podemos ir a su pareja.

*** GIF 8

![Modo normal](/img/08.gif)

Si queremos hacer una búsqueda, podemos hacer uso de la tecla "/". Luego, con las teclasa "n" y "N" podemos mostrar los 
siguientes o anteriores resultados de la búsqueda.

*** GIF 9

![Modo normal](/img/09.gif)

Para añadir una fila nueva tenemos dos posibilidades. Pulsar la tecla "o" o "O", añade una fila nueva y entra
en modo inserción. Otra opción es acceder al modo "inserción" y hacer uso de la tecla "INTRO" situándonos donde
queramos añadir una fila nueva.

*** GIF 10

![Modo normal](/img/10.gif)

Si queremos cambiar un caracter sin entrar a modo inserción, podemos hacer uso de la tecla "r". Una vez activada
con seleccionar la tecla que queramos, sustituirá la que esté marcada por el cursor.

*** GIF 11

![Modo normal](/img/11.gif)

Si queremos borrar podemos hacer uso de la letra "d". También podríamos entrar a modo edición y borrarcon la tecla
"SUPR" o "RETROCESO". Si queremos borrar una palabra podemos hacer uso de la combinación "dw". Realmente no la borra sino
que la corta por ello, con la letra "p" podemos pegar donde queramos dicho contenido.

*** GIF 12

![Modo normal](/img/12.gif)

Si queremos podemos borrar una fila entera haciendo uso de la letra "dd". Como antes, realmente se está cortando
dicho contenido por lo que con la tecla "p" podemos pegar lo copiado donde queramos.

*** GIF 13

![Modo normal](/img/13.gif)

Con la tecla "." (punto), podemos repetir la última acción. Por eejmplo, si cortamos un contenido podemos pegarlo
en varias ocasiones pero recuerda, es repetir la última acción, sea la que sea.

*** GIF 14

![Modo normal](/img/14.gif)

Si deseamos seleccionar un texto entraremos en modo visual pulsando la tecla "v", momento en el cual ya comenzará
la selección. Una vez seleccionamdo lo deseado, con la tecla d podemos borrar dicho contenido. Si quisieramos podríamos
pegar dicho contenido en otro sitio.

*** GIF 15

![Modo normal](/img/15.gif)

Co la letra "yy" copiaremos la línea en la que nos encontremos. Con la letra "p" podemos pegar dicho contenido.

*** GID 16

![Modo normal](/img/17.gif)

Con la letra "S" borraremos la línea en la que nos encontremos. En nuestro caso muy parecido a "dd".

Con ":w" podemos grabar los cambios.

Con ":q" podemos salir

Con "q!" saldremos sin grabar cambios.

Con ":u" desharemos cambiamos y con "CTRL+R" reharemos cambios.

Para acceder a la ayuda podemos hacer uso de ":help".



