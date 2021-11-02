# project1-game-DOM

##**The fastest teacher

El juego está planteado mediante DOM. Su lógica es sencilla, como jugador tenemos que clickar sobre las hojas de exámenes que aparezcan en nuestro contenedor para darles el aprobado lo más rápidamente posible.
Cada examen actuará como un *elemento*, un **botón**, el cual quedará constancia de su interactuación de selección al clickar sobre ella.

Estos elementos tendrán un intervalo de tiempo de 2 segundos de aparición, de no haber seleccionado el elemento, se restarán una serie de puntos.

La puntuación se ejecutará mediante una función de suma condicionada si se selecciona a tiempo el elemento (suma) o no (resta), el juego acabará transcurrido un minuto desde el inicio de la partida, donde nos encontraremos la puntuación final en pantalla.

La aparición de los elementos abarcará un ancho de 900px por otros 900px de largo para mayor mobilidad.
