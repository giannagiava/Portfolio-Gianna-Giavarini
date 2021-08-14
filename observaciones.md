# Observaciones

Gianna, felicitaciones por tu trabajo. Es increible el nivel de atención al detalle que demostras con este trabajo: cada espaciado, cada linea, se nota que está pensada y repensada para seguir a la perfección el modelo de Ada. Me gusta además cómo le diste tu estilo con los colores y las imágenes. El resultado es una web que te refleja y a la vez cumple a la perfección lo solicitado.

Tengo, lamentablmemente, pocos comentarios para hacerte, ya que el nivel de este trabajo es realmente muy alto. Pero siempre hay algo que comentar! :) Como dije en clase, este trabajo no se hace para que constates conocimientos, sino para que aprendas: en ese sentido, mi intencion es que estos comentarios te sirvan para aprender, mejorar tu codigo a futuro e ir apreciando mejor qué se espera de nosotras como desarrolladoras front end.

## Estructura correcta de documento HTML

Tu HTML esta realmente excelente. Claro, prolijo, muy bien comentado e identado.

Tenés cierta tendencia a tener divs de más. Algunas estructuras de tu web se podrían resolver con menos divs. Dicho esto, yo prefiero que los divs sobren antes de que falten: un div de más se soluciona muy fácil, un div menos puede ser un gran dolor de cabeza cuando estamos recién arrancando. Este sería un comentario que quizá me reservaría para futuros trabajos, pero veo tan bien tu código que me siento confiada en recomendarte que empieces a ver estas cosas desde ya. 

Utilizás ocasionalmente etiquetas `br` para separar las cosas: no llegué a comentarlo en clase, pero esto es incorrecto. Esa etiqueta es un resabio de viejas épocas en las cuales css no era tan poderoso como ahora, pero usarla hoy viola uno de los principios básicos de programación: la separación de responsabilidades. Los estilos se dan con css, la estructura se da con html. Una decisión de estilo como un espaciado entre dos elementos debe controlarse con css -flex, elementos en bloque, etc, no con `br`. 

Tus imagenes tienen el atributo "role=img", lo que es absolutamente innecesario. Usamos ese atirbuto en los iconos, para que el lector de pantalla no los ignore, pero en las imagenes no se necesita. 


## Respeta la consigna

- El portfolio cuenta con las secciones solicitadas
- Al clickear en los links de navegación, debe llevar a la sección correspondiente
- Al clickear en los links de contacto, debe llevar a la página externa
  correspondiente
- El portfolio debe tener un diseño responsivo y verse correctamente en distintos dispositivos
- El portfolio debe estar deployado y ser accesible desde una URL
- El repositorio en GitHub debe tener un readme adecuado

Todos estos puntos están cumplidos. Menciono especialmente tu responsive: es increíble lo bien que solucionaste las distintas resoluciones, siguiendo casi a la perfección el modelo y preocupandote para que todo se vea hermoso, veamos tu web desde cualquier dispositivo. 

### Respeta el diseño dado

Cumplido a la perfección. 

### Buena estructura de proyecto

Cumplido casi a la perfección, pero el favicon deberia estar en la carpeta principal (en mi computadora no se ve, por ejemplo). Notá también que tenés una carpeta innecesaria, `vscode`, que es agregada a veces automáticamente por Visual Studio. Es buena práctica borrarla antes de una entrega. 

### Código bien indentado

Tabulas muy bien, lo cual parece un detalle extra cuando una recien comienza pero ayuda un monton a su legibilidad, y que lo hayas logrado en esta etapa es un gran mérito. 

En tu CSS el tabulado está perfecto, pero no dejas el espaciado correcto en cada orden. En lugar de escribir por ejemplo `.name{`, deja un espacio entre el nombre de la clase y la llave: `.name {`

### Comentarios que permiten mejorar la legibilidad del código

Los comentarios en HTML tienen el siguiente formato:

<!–– Estilos letras --> 

Vos le agregas un espacio al princpio, lo que puede generarte errores en algunos navegadores.

### Uso correcto de etiquetas semánticas

En general usas bien las etiquetas semánticas. Me llama la atención que hayas usado `div` para las tarjetas de Mis Conocimientos: yo diría que deberían ser `article`. Pero es el único detalle a comentar aquí (y hay quien podría discutirme que deberían ser divs)

### Buenos nombres de clases

Cumplido.

### Código CSS bien estructurado

Cumplido

### Reutilización de estilos

Cumplido en general, ya que noto muchas veces que usas dos nombres de clase, uno general y otro más específico, para evitar repeticiones innecesarias, como en los íconos de mis proyectos. Podrías mejorarlo, por ejemplo en el código de las secciones que te indiqué más arriba: si todas van a tener el mismo width en distintos media queries, por qué no subsumirlos en una clase contenedora? 

### Cumple con criterios básicos de accesibilidad

- Los colores tienen un contraste adecuado

Cumplido en general, aunque en algunos casos se te escapa: en el hover de los links de la barra de navegación por ejemplo. Siempre chequeà con https://webaim.org/resources/contrastchecker/

- Las imágenes tiene el atributo `alt` que corresponde

Incumplido, como vimos en clase el lector de pantalla dice "Imagen" antes de leerlo asi que agregar "imagen" es repetitivo, y las imagenes decorativas son aquellas como bordes, no una imagen que describe tu proyecto o que representa algo. Tu web debe ser accesible, y eso incluye tus imagenes: la mujer usando traje que pones en la portada comunica algo a tus usuarios videntes, y debes encontrar la manera de transmitirle esa información a quienes no pueden verla. 

- Los íconos y elementos que no presentan texto agregan la información correspondiente por otros medios (etiquetas aria, texto oculto)

Cumplido

- Los íconos y elementos que no necesitan ser anunciados por un lector de pantalla tienen la etiqueta aria
  correspondiente

Cumplido

- Commits con mensajes adecuados

Cumplido, noto muchos y buenos commits en tu proyecto, lo que siempre se agradece.

- Cuenta con un favicon

Cumplido, aunque debería estar en la carpeta principal

### Nota: 9
