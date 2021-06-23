# HTML.__GB__


## Elementos de bloque

Para representar que estamos siguiendo el estandar html 5
```http
 <!DOCTYPE html>
```
Especifica el lenguaje del archivo
 ```http
  <html lang='es'>
 ```
 Para especificar el set de caracteres latino podemos usar
  ```http
  <meta charset="UTF-8">
 ```
 ## Head
 Para representar una coleccion de datos o metadatos informacion que le vamos a pasar al nevegador sobre nuestra pagina
 
 ```http
  <head>
    <meta name='viewport' content=''> //estos no ayudan a trabajas el responce
    <meta name='description' content='algoQueDescribeLaPagina'> //esto nos ayuda a hacer visible nuesta pagina en el buscador de google le grega una description
    <meta name='author' content='gabriel'> //nos muestra el author>
    <link rel='' sizes='' href=''> // esto nos pone un favicon el el titulo de la pagina (https://www.favicon-generator.org/)
    
 ```
 Para poner lo que queremos poner en la patalla como title usamos
 ```http
  <title>
 ```
 Para representar todo el contenido de nuestra web usamos 
 ```http
  <body>
 ```
 el titulo de una seccion le damos principal
 ```http
  <h1>
 ```
 el comienso de una seccion dentro del h1 le indicamos con
 ```http
  <h2>
 ```
 y asi sucesivamente con los <hn> cada <hn> menor que debe pertenecer a una <hn> mayor que no estar solas sin coneccion
 ```http
  <h1>
  <h2>
  <h3>
  <h3>
  <h4>
  <h5>
  <h6>
 ```
 el tag <p es para rellenar con  texto
 ```http
  <p>
 ```
 ## Header-Main y Footer dentro del Body
   
 header es la cabecera de nuestra pagina
 ```http
  <header>
 ```
 ```http
  <header> menu de navegacion / logo / redes sociales <header/>
 ```
 main es el contenido de nuestra pagina
 ```http
  <main>
 ```
 el pie de pagina es footer
 ```http
 <footer>
 ```
 cuando creamos bloques cuyo contenido es parte de un bloque total usaremos
   ```http
  <section>
 ```
 si queremos poner un fragmento en cualquier sitio con contenido independiente usamos
   ```http
  <article>
 ```
 para agregar contenido relacionado pero que no forma parte del contenido principal usamos 
  ```http
  <aside>
 ```
## Elementos de linea
 emphasis
 ```http
  <em>
 ```
 mas enfasis
  ```http
  <strong>
 ```
 Menos enfasis que el texto normal
  ```http
  <small>
 ```
 Forzar un salto de linea
  ```http
  <br>
 ```
 salto de linea si hiciera falta
  ```http
  <wbr>
 ```
 Se usa para representar un contenido de hora y fecha
  ```http
  <time>
 ```
 <i>italic</i> tambien se usa para aniadir iconos
  ```http
  <i>
 ```
 <b>bold</b>
 ```http
  <b>
 ```
 <u>underline</u>
 ```http
  <u>
 ```
 superindice 4<sup>2</sup>
 ```http
  <sup>
 ```
   subindice H<sub>2</sub>
 ```http
  <sub>
 ```
 # Atributos
   ## Estos proveen informacion adicional sobre un elemento o etiqueta a la vez que lo modifican 
   
 alinear al centro 
   ```bash
   align="center"
   ```
   la relacion entre el documento que vamos a coger y el documento
   ```http
  rel=''
 ```
   para dar estilo atraves de css podemos usar 
 ```http
  class=''
 ```
  para hacer navegacion atraves de anclas y seleccionar elementos para css podemos usar 
 ```http
  id=''
 ```
 para que aparesca el mensaje en un tooltip (ayuda a la accesibilidad mostrando una descripcion del elemento
  ```http
  tiitle=''
 ```
  para poner el link de donde viene una frase o algo usamos
 ```http
  cite=''
 ```
 si nesecitamos guardar algun valor en la etiqueta html podemos usar data-algunnombre
 ```http
  data-ejemplo='alguna informacion que quisieramos consologuear '
 ```
   para mandar al usuario a una nueva ruta sin que pierda nuestra pagina unamos 
 ```http
  target='_blank'
 ```
  si queremos que el usuario pueda descargar al go desde nuestra pagina usamos
  ```http
  download=''
 ```
 le podemos dar un poco de estilo desde html mira esto
 ```http
  type='circle'
 ```
  para decirle al navegador a que categoria pertenece algo un input o lo que sea usamos
  ```http
  name=''
 ```
 ## Enlaces
   si queremos mmovernos en la web nesecitamos enlaces aqui hay uno
  ```http
   <a href=''></a>
 ```
 ## Navegacion con anclas
   si queremos navegar por nuestra pagina y que nos lleve a algun post podemos usar
  ```http
   <a href='#nombredelIdDelTag'></a>
 ```
 ## Listas
   ul se utiliza cuando el orden de los elementos no influyen
 ```http
  <ul>
 ``` 
   ol se utiliza cuando el orden de los elementos es importante
 ```http
  <ol>
 ```
    dl se utiliza para hacer una lista de definiciones
 ```http
  <dl>
     <dt>title
      <dd>content
 ```
 # Introduccion a las tablas
     la etiqueta que encierra la taabla
 ```http
  <table>
 ```
   la etiqueta que construye la fila
  ```http
  <tr>
 ```
   la etiqueta que construye una celda las columnas de nuestra tabla
  ```http
  <td>
 ```
  los titulos de las tablas se  establesen con el tag caption
   ```http
  <caption>
 ```
  las cabeceras de las tablas se establesen con la etiqueta thead y establece grupos dentro de la tabla 
 ```http
  <thead>
 ```
 si tenemos thead tenemos que tener un tbody rodeado nuestra tabla
```http
  <tbody>
 ```
 para establecer un pie de tabla usamos
 ```http
  <tfoot>
 ```
 ## Atributos de las tablas
   para hacer que las celdas ocupen mas de una fila valor por defecto 1
   ```http
  rowspan=''
 ```
  para hacer que una celda ocupe mas de una coumna valor por defecto 1
 ```http
  colspan=''
 ```
 ## Etiquetas de bloque
   para aportar diraccion de contacto para un article o todo el body usamos
  ```http
  <address>
 ```
 blockquote se utiliza par marcar las citas a otros autores o docun=mentos tambien un enlace
  ```http
  <blockquote>
 ```
para escribir alco tipo codigo que va a ser representado tal y como se escribio
 ```http
 <pre>
 ```
si queremos un contenedor generico para dar estilos o para usar algo denominado 'delegacion de eventos' en javascript usamos 
 ```http
  <div>
 ```
 si queremos cambiar de tema en la pagina le podemos decir al navegador que tenga encuento un hr
  ```http
  <hr>
 ```
## Etiquetas de linea
si queremos un contenedor de linea para enserrar textos y darles estilos o localizarlos a travez de js podemos usar
 ```http
  <span>
 ```
si queremos un equivalente a blockquote pero en linea que sirve para poner citas tenemos 
 ```http
  <q>
 ```
si vamos a escribir codigo tenemos que usar 
 ```http
  <code>
 ```
## introduccion a los formularios
la etiqueta que engloba nuestro formulario es
 ```http
  <form>
 ```
para escribir el nombre del campo a rellenar
 ```http
  <label>
 ```
para crear un campo que permitira al usuario interactuar
 ```http
  <input>
 ```
para crear bottones
 ```http
  <button>
 ```
 ## input types
 si queremos tener un button que no envie un formulario sino que lo vamos a trabajas deste js usamos
  ```http
  type='button'
 ```
 si queremos enviar un formulario usamos
  ```http
  type='submit'
 ```
 si queremos introducir una fecha en el input usamos
 ```http
  type='date'
 ```
 y si queremos introducir la hora usamos 
  ```http
  type='time'
 ```
 si queremos elegir un mes usmos
  ```http
  type='month'
 ```
 si queremos selecciona una semana vala saver una para que
 ```http
  type='week'
 ```
 ## inputs para moviles
 para barras de busqueda
 ```http
  type='search'
 ```
 para introducir numeros de telefono
 ```http
  type='tel'
 ```
 para introducir un email
 ```http
  type='email'
 ```
 para introducir contracen:as
 ```http
  type='password'
 ```
 para introducir url 
 ```http
  type='url'
 ```
 ## input extra
 para especificar un color
 ```http
  type='color'
 ```
 si le queremos dar un width porque ya sea vamos a trabajar movimiento de la img con js entonses usamos width desde el html
 ```http
  width='300'
 ```
 para valores numericos
 ```http
  type='number'
 ```
 para establecer un rango crea una barra tipo las de volumen
 ```http
  type='range' step='5' min='0' max='20'
 ```
 para resetear el formulario
 ```http
  type='reset'
 ```
 valor por defecto
 ```http
  type='text'
 ```
 for liga los imputs o algo
 ```http
  <label for='liga'>
  <input id='liga'>
 ```
 ## type of input para seleccionar todas iran dentro de una etiqueta option
 
 para seleccionar una unica opcion de una unica lista de opciones relacionadas
 ```http
  type='radio'
 ```
 para seleccionar varias opciones dentro de una lista relacionadas
 ```http
  type='checkbox'
 ```
 para crear/desplegar una lista de opciones donde podemos seleccionar una o varias opciones
 ```http
  <select>
  tiene una variente con la etiqueta multiple
 ```
 ```http
 si tenemos muchas opciones podemos ordenarlas por categorias a traves de la etiqueta <optgroup> con el atributo label para nombrar la categoria
 ```
 un tag que es un poco mas estetico es datalist la forma correcta de usarla es la siguiente tambien filtra por busqueda
 ```http
  <input Type='list' list='pets'>
  <datalist id='pets'>
     <option value='perro'>Perro</option>
     <option value='perro'>Perro</option>
     <option value='perro'>Perro</option>
  </datalist>
 ```
 si queremos darle un borde agrupar los elementos dentro de un form usamos
 ```http
  <fieldset>
 ```
 para darle una etiqueta el contenido de fieldset usamos
 ```http
  <fieldset>
       <legend>
 ```
 si queremos cargar un archivo de nuestro pc usamos un input type
 ```http
  type='file'
 ```
 meter es un valor que representa un rango conocido es vistoso mostrara colores dependiendo de low high
 ```http
  <meter id='fuel' min='0' max='100' value='50' low='30' high='75' optimun='50'>
 ```
 progress representa el progreso  de una tarea
 ```http
 <progress id='task' max='100' value='75'></progress>
 ```
 para agregar un campo de tarea
 ```http
  <textarea cols='30' rows='10'>
 ```
 ## atributos para formularios
 da una pista de lo que el usuario tiene que introducir
 ```http
  placeholder='pista'
 ```
 para hacer que un campo sea obligatorio
 ```http
  required
 ```
 para hacer que un campo sea solo lectura 
 ```http
  readonly
 ```
 para desactivar un campo que no se pueda escribir en el ni enviar usa
 ```http
  disabled
 ```
 para poner un limite de min y max en un campo numerico podemos usar 
 ```http
  min='' max=''
 ```
 para poner un limite de minlength y maxlength en un campo de text usamos
 ```http
  minlength='' maxlength=''
 ```
 selected  equivale a checked en los select, sirve para establecer una opcion por defecto
 ```http
  <option value='Two' selected>
 ```
 para poner el foco por defecto al cargar el formulario se usa 'autofocus'
 ```http
  <option value='Two' selected autofocus>
 ```
 # Envio get vs post
 El metodo GET es el que se ejecuta cuando entramos a una pagina atrabes de la url
 ```http
  method='GET'
 ```
 para el envio de formularios atraves de atras de la pagina es decir busca el archivo para enviar la info
 ```http
  method='POST'
 ```
 la plantilla name es obligatoria si se van a enviar datos si noo los pones es como si el campo no existiera
 ```http
  name='algo'
 ```
 # contenido enbebido
 ## imagenes
 ###vectoriales
 -svg(recomendodo siemmpre que se pueda no pierde calidad nunca porque el que renderiza los colores es el browser no an:ade peso a la pagina)
 ### Mapa de bits
 -jpg
 -png 8 y 24 (si necesitas transparencias)
 -gif (si necesitas una imagen animada)
 -webp (el formato que menos pesa hay que convertie la imagen usando alguna web)
 ## insertar imagenes en HTML
 para usar imagenes nesecitamos la etiqueta img que la imagen se desborde no es un tema de html
 ```http
  <img src='ruta' alt='mensage alternativo para la no carga o invidentes'>
 ```
 ## Atributo srcset
 bueno para decirle al navegador que carge una imagen diferente dependeniendo el DPR (escritorio o celu) usamos dos imagenes y (el 3x le dice cuando cambiar de imagen dependiendo el DPR
 ```http
  <img srcset='/alguna/imagen/pc,  /alguna/img/movile 3x' alt =''>
 ```
 tambien podemos usar picture pero nos pude por default que agreguemos una url de seguridad por si no es compatible
 ```http
 <picture>
    <source srcset='' media='(mex-width:1200px)'>
       <img src='' alt=''>
 ```
 ## Etiqueta audio
 para colocar audio 
 ```http
  <audio src='/contenido/audio' controls autoplay muted>
 ```
 ## Etiqueta video
 para colocar video
 ```http
  <video src='' controls autoplay muted loop poster='/alguna/imagen/posterantesdelvideo'>
 ```
 ##inframes
 no es buena idea sobrecargar nuestra web con iframes por el peso que le estamos poniendo inspecciona un iframe y lo veras
 ```http
  <inframe>
 ```
 ## Etiquetas
 si queremos agregar contenido opcional usamos
 ```http
  <figure>
 ```
 para darle titulo a ese contenido 
 ```http
 <figcaption>
 ```
 ## Atributos de accesibilidad
 se usa para poder darle mas accesibilidad valla a saver uno que onda ejemplo
 -si queremos poder con solo apretar tab movernos de elementos en la pegina
  ```http
  tabindex='1'
  tabindex='2'
 ```
 si le queremos dar mas informacion a una pagina para no videntes en los link
 ```http
  aria-label='lo que quieras poner'
 ```
 
 ## Open Graph protocol (ogp.me)  para twitter (developer.twitter.com)
 
 
 
 
