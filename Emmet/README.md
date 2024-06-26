p# TRUCOS Y HACKS DE EMMET
### Cuando creamos un archivo con extensión .html:
- **!** → Si escribimos "!" al inicio de una página html y le damos a intro, nos aparecerá un esquema simple de una página html
- **html:5** → Es lo mismo que escribir "!" al inicio <br>

En ambos casos nos aparecerá esta estructura: <br><br>
![Puedes ver un ejemplo aquí](https://github.com/CrisCorreaS/trucos-vscode/blob/main/Emmet/Videos/html.gif)

### Dentro de la etiqueta head de un archivo con extensión .html:
- **link:css** → Si dentro de la etiqueta "head" escribimos "link:css" y le damos a intro nos aparecerá ``<link rel="stylesheet" href="style.css">``
- **script:src** → Si escribimos "script:src" nos aparecerá ``<script src=""></script>``
- **script:modules** → Si escribimos "script:module" podremos trabajar con módulos en js directamente ya que nos aparecerá ``<script type="module" src=""></script>``

### Dentro de la etiqueta body de un archivo con extensión .html
- **lorem** → Crea una línea de texto de Lorem Ipsum
- **lorem2** → Crea dos palabras de lorem → Si ponemos lorem + número (ej: lorem5) se genera el número de palabras de lorem que hemos especificado. <br> _Ej:_ lorem7 = ``Lorem ipsum dolor, sit amet consectetur adipisicing.``
- **lorem*30** → Crea 30 líneas de texto de Lorem Ipsum → Si ponemos lorem + * + número (Ej: lorem*5) se genera el número de líneas de lorem que hemos especificado. <br> _Ej:_ lorem*2: <br>
(línea 1) ``Lorem ipsum dolor sit amet consectetur adipisicing elit. Nihil quasi soluta dicta ratione! Modi nostrum error obcaecati magni consectetur. Magni odit provident totam numquam cumque tempora fugit. Amet, omnis explicabo?<br> 
(línea 2) ``Quidem reprehenderit culpa distinctio, quis atque dolore ea, corporis quod harum ipsa, vero suscipit officia. Ipsa adipisci voluptatem quaerat autem in, illum nobis architecto quisquam reiciendis quas, inventore repudiandae sapiente!`` 

- **p>lorem15** → Crea un párrafo con quince palabras de Lorem Ipsum. <br> _Ej:_ 
``<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero, numquam. Dolorem eveniet itaque et impedit?</p>``

- **p+a** → Si escribimos "p+a" y hacemos intro, aparecerá una etiqueta "p" y en el mismo nivel, una etiqueta "a". Se parece mucho a los selectores de css. <br> _Ej:_ <br>
```
<p></p>
<a href=""></a>
```

- <b>p+a\*2</b> → Si escribimos "p+a\*2" y hacemos intro, aparecerá una etiqueta "p" y en el mismo nivel, dos etiquetas "a". <br> _Ej:_ <br>
```
<p></p>
<a href=""></a>
<a href=""></a>
```

- <b>(p+a)*2</b> → Si escribimos "(p+a)*2" y hacemos intro, aparecerán en el mismo nivel una etiqueta "p", una etiqueta "a", seguida de otra etiqueta "p" y de otra "a". <br> _Ej:_ <br>
```
<p></p>
<a href=""></a>
<p></p>
<a href=""></a>
```

- **p{Parrafo}** → Si escribimos una etiqueta y abrimos y cerramos llaves, el contenido entre las llaves, va a ser el texto que está entre las etiquetas de apertura y cierre. <br> _Ej:_
``<p>Parrafo</p>``

- **p#parrafo1** → Si escribimos una etiqueta seguida de un hashtag con una palabra, se creará esa etiqueta con un atributo "id" que tenga el valor igualado a esa palabra. Se parece mucho a los selectores de css. <br> _Ej:_
``<p id="parrafo1"></p>``

- **p.parrafos** → Si escribimos una etiqueta seguida de un punto y una palabra, se creará esa etiqueta con un atributo "class" que tenga el valor igualado a esa palabra. Se parece mucho a los selectores de css. <br> _Ej:_
``<p class="parrafos"></p>``

- **pre#texto-preformateado1.texto** → Crea una etiqueta "pre" con un atributo id="texto-preformateado1" y un class="texto". <br> _Ej:_
``<pre id="texto-preformateado1" class="texto"></pre>``

- **p>b** → Si escribimos "p>b" significa que crearemos una etiqueta "p" que a su vez, contenga una etiqueta "b". <br> _Ej:_
``<p><b></b></p>``

- <b>table>(tr>th*3)+((tr>td*3))*2</b> → Creará una tabla con un "tr" que tenga anidados tres "th" y dos "tr" que tengan anidados, cada uno, tres "td". <br> _Ej:_ <br>
```
<table>
  <tr>
    <th></th>
    <th></th>
    <th></th>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>
```
  
- <b>p#parrafo$${Este es el párrafo $$}*11</b> → Si ponemos una etiqueta seguido de un hashtag con una palabra, abrimos y cerramos llaves con un texto y lo multiplicamos por once, nos crea once etiquetas con un id y un texto dentro. El dólar es un símbolo dinámico, que toma el valor de cada uno de los números del 1 al número por el que lo hayamos multiplicado en nuestro código. El dólar se puede poner en cualquier texto que queramos que sea dinámico, en este caso lo usamos tanto en el id como en el texto de cada elemento. <br> _Ej:_ <br>
```
<p id="parrafo01">Este es el párrafo 01</p>
<p id="parrafo02">Este es el párrafo 02</p>
<p id="parrafo03">Este es el párrafo 03</p>
<p id="parrafo04">Este es el párrafo 04</p>
<p id="parrafo05">Este es el párrafo 05</p>
<p id="parrafo06">Este es el párrafo 06</p>
<p id="parrafo07">Este es el párrafo 07</p>
<p id="parrafo08">Este es el párrafo 08</p>
<p id="parrafo09">Este es el párrafo 09</p>
<p id="parrafo10">Este es el párrafo 10</p>
<p id="parrafo11">Este es el párrafo 11</p>
```

- <b>ul>li.list-item{Elemento $}*11</b> → Crea un "ul" con once elementos "li", cada uno de esos elementos tiene un atributo "class" igual y un texto dinámico gracias al dólar. <br> _Ej:_ <br>
```
<ul>
  <li class="list-item">Elemento 1</li>
  <li class="list-item">Elemento 2</li>
  <li class="list-item">Elemento 3</li>
  <li class="list-item">Elemento 4</li>
  <li class="list-item">Elemento 5</li>
  <li class="list-item">Elemento 6</li>
  <li class="list-item">Elemento 7</li>
  <li class="list-item">Elemento 8</li>
  <li class="list-item">Elemento 9</li>
  <li class="list-item">Elemento 10</li>
  <li class="list-item">Elemento 11</li>
</ul>
```

- <b>ol#calles&gt;li{Calle $@10}*4</b> → Crea un ol con un id="calles" con cuatro elementos "li", en cada uno de ellos aparece un texto dinámico. Al poner $@10, indicamos que el dólar empieza desde el número 10 inclusive. <br> _Ej:_ <br>
```
<ol id="calles">
  <li>Calle 10</li>
  <li>Calle 11</li>
  <li>Calle 12</li>
  <li>Calle 13</li>
</ol>
```

- <b>div>(div.container>img.foto+p#foto$-titulo)*4</b> → crea un "div" con cuatro "div" diferentes con la misma class="container" y que a su vez, cada div de clase container tiene una etiqueta "img" de class="foto" y un "p" con un "id" dinámico. <br> _Ej:_ <br>
```
<div>
  <div class="container">
    <img src="" alt="" class="foto">
    <p id="foto1-titulo"></p>
  </div>
  <div class="container">
    <img src="" alt="" class="foto">
    <p id="foto2-titulo"></p>
  </div>
  <div class="container">
    <img src="" alt="" class="foto">
    <p id="foto3-titulo"></p>
  </div>
  <div class="container">
    <img src="" alt="" class="foto">
    <p id="foto4-titulo"></p>
  </div>
</div>
```

- <b>(div.post>h2.title+span.date+div.content>lorem)*5</b> → Crea cinco divs de class="post" que dentro tienen un h2 con un class="title", un span con un class="date" y un div con un class="content" y dentro un texto de Lorem Ipsum. <br> _Ej:_ <br>
```
<div class="post">
  <h2 class="title"></h2>
  <span class="date"></span>
  <div class="content">
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Adipisci, nihil deserunt? Distinctio sunt in ex et doloribus magni minima corporis illo pariatur cum dolorem, est quam modi deserunt dicta recusandae?
  </div>
</div>
<div class="post">
  <h2 class="title"></h2>
  <span class="date"></span>
  <div class="content">
    Culpa vitae, sed quidem placeat vel animi ipsum consectetur cum laborum laudantium quas enim aliquid nostrum, vero esse delectus asperiores minus quis beatae. Reprehenderit fugiat corporis nemo sunt facilis repellendus.
  </div>
</div>
<div class="post">
  <h2 class="title"></h2>
  <span class="date"></span>
  <div class="content">
    Aliquid laborum eos blanditiis deserunt vel asperiores eum odit quae! Velit dolorum libero rerum, explicabo nemo, ea accusamus rem commodi quia obcaecati placeat. Ullam eveniet, deserunt illo consequatur quia voluptas?
  </div>
</div>
<div class="post">
  <h2 class="title"></h2>
  <span class="date"></span>
  <div class="content">
    Vel nisi distinctio vero, ab voluptatibus eligendi corporis veniam dolorum molestias excepturi cum voluptatem maxime iusto ullam natus. Molestiae, qui. Officiis optio veniam iure doloremque facere quisquam, pariatur debitis explicabo.
  </div>
</div>
<div class="post">
  <h2 class="title"></h2>
  <span class="date"></span>
  <div class="content">
    Est dolor quam, adipisci tempore, consectetur obcaecati tempora, ipsam commodi a tenetur nulla repellendus aperiam incidunt quisquam. Nisi velit provident possimus, quia assumenda quibusdam ducimus totam adipisci voluptatem iste pariatur!
  </div>
</div>
```
