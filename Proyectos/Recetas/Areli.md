# Proyecto recetas - Areli

¡Felicidades! Tu proyecto cumple muy bien con su objetivo. Lograste definir estructuras con html y 
crear enlaces entre diferentes archivos, lo cual es el primer paso que todos tomamos cuando aprendemos
desarrollo web. Tu repositorio tiene 22 commits, **lo cual es una excelente práctica** porque de esta manera
se hace mucho más fácil colaborar en equipo, corregir accidentes, y al mismo tiempo se va formando una especie de
narrativa acerca de qué es lo que ha cambiado en tu proyecto. Sin embargo, pienso que los mensajes de commit 
podrían mejorar ya que actualmente no son muy descriptivos, por ejemplo, el mensaje `anexo imagen`
podría también informar a qué archivo le estás añadiendo la imagen, o cuál es la función de esa imagen, se me ocurre algo como:
`Anexo imagen del platillo terminado en cochinita.html`.

Otra práctica muy positiva que observo es que decidiste crear una carpeta para almacenar las imagenes. Más adelante
aprenderemos que en programación uno de los principios más importantes es separar los archivos dependiendo de su naturaleza,
y tú lo has aplicado muy bien en este caso.

Por otro lado, hay algunos _detalles_ que creo que pudieron haber sido diferentes:
* En las tres recetas usas la etiqueta `h1` para el nombre de la receta, los pasos e ingredientes
Pero esta se debió haber usado solo para lo principal, que en este caso es el nombre de la receta,
para los pasos e ingredientes pudiste haber usado `h2`
* En `index.html` hay un error tipográfico, en la línea 11 está escrito `target="_blnk"` y debería ser `target="_blank"`
* En `index.html` la etiqueta `ol` no está cerrada
* La práctica sugería utilizar una lista no ordenada para enlistar las recetas, sin embargo tú utilizaste una lista ordenada
Entiendo que posiblemente tuviste alguna razón para ello, pero pudiste haberla especificado en un comentario html
* En `horchata.html` línea 9 escribiste `width"400"`, de nuevo un error tipográfico, ya que debió haber sido `width="400"`
* La etiqueta `title` de los cuatro documentos es la misma: `Document`, pienso que pudiste haber elegido un `title` más amigable con los usuarios

| Rubro | Parcial | Peso | Puntos |
| -- | -- | -- | -- |
| Existe un archivo `index.html` y un `h1` con el texto `Odin Recipes` | 10 | 0.1 | 1.0 |
| Existe un archivo html con el nombre de cada receta | 10 | 0.1 | 1.0 |
| Cada archivo con la receta incluye un `h1` con el nombre de la receta | 10 | 0.1 | 1.0 |
| Existe y funciona correctamente un link en `index.html` con el nombre de la receta | 10 | 0.3 | 3.0 |
| Cada receta cumple con la estructura adecuada | 7 | 0.2 | 1.4 |
| Existen al menos tres recetas y sus respectivos links funcionando | 10 | 0.2 | 2.0 |
| **Total** | -- | -- | 9.4 |
