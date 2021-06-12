# HTML.__GB__
&lt;i> tag
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
 Para representar una coleccion de datos o metadatos informacion que le vamos a pasar al nevegador sobre nuestra pagina
 
 ```http
  <head>
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
 ## atributos
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
 ## introduccion a las tablas
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
   
