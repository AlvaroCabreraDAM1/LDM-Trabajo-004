# Lunar Lander. HTML y CSS.

Enlace a la página: 
https://rawgit.com/AlvaroCabreraDAM1/LDM-Trabajo-004/master/lunarLander.html

### Contenido del repositorio:
 
- 2 archivos html, uno para el juego y otro para la pantalla de instrucciones.
- Una carpeta con las imágenes usadas.
- Una carpeta con 4 archivos css (2 para el juego y 2 para la página de instrucciones).
- Una ramificacion con el código comprimido. 
  Enlace a la ramificacion: 
  
  https://github.com/AlvaroCabreraDAM1/LDM-Trabajo-004/tree/Compresed-code
  
  Enlace a la pagina con el codigo comprimido: 
  
  https://rawgit.com/AlvaroCabreraDAM1/LDM-Trabajo-004/Compresed-code/lunarLander.html

### Modificaciones respecto al modelo inicial:

- Modificación del medidor de gasolina: He modificado ligeramente el diseño del indicador para que no muestre el porcentaje de gasolina.
Esto se ha hecho debido a que, con la ayuda del diseñador, llegamos a la conclusión de que el jugador no se fijaria en el medidor de
aguja y se centraría en el porcentaje, ya que ofrece una información más directa sobre el estado del depósito. El objetivo del medidor
de aguja es que el jugador tenga una experiencia más realista, y un medidor en forma de porcentaje no le daría esa sensación.

- Modificación de la disposición de los medidores: He desplazado los medidores de gasolina, altura y velocidad para que queden más
centrados en la parte izquierda de la pantalla.

- Modificación de la paleta de colores: Los colores de algunos elementos han sido modificados para que se ajusten a un diseño y una
paleta común.

- Modificación del fondo: El diseñador se encargó de proporcionar un fondo más adecuado para el estilo del proyecto, ya que el anterior
desentonaba con el resto de elementos.

### Estructura de los divs:

Estructura principal: La estructura fundamental del proyecto está basada en 3 divs, que contienen el resto de elementos. Estos 3 divs
son 

- Div de los medidores: Este div contiene todos los medidores que hay en el juego. En la versión para PC ocupa un 25% del ancho de la
pantalla y está situado a la izquierda. En la version de movil está situado en la parte derecha y ocupa un 30% del ancho de la pantalla.

- Div principal: Este div contiene la nave y la luna. Ocupa un 50% del ancho de la pantalla en ambos modelos y siempre está situado en
el centro de los otros dos.

- Div de los botones: En este div están contenidos todos los botones funcionales del juego, también los respectivos menús que los
contienen. Está situado a la parte derecha en el PC y ocupa un 25% del ancho de la pantalla. En el modelo de smartphone ocupa un 20% y
está situado en la parte izquierda. Hay botones que se ven desplazados a la parte derecha, pero siguen estando contenidos en este div.

Div menu o contenedor de opciones: Este div se encarga de contener los botones que modifican las opciones del juego, como los cambios de
skin. En la versión de PC no tiene fondo y se sitúa en la parte superior derecha de la pantalla. En la version de movil tiene un fondo y
se presenta en forma de un menú que aparece al pulsar el botón de opciones.
