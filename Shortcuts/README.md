# SHORTCUTS DE VSCODE
## En una terminal como PowerShell
- **`code .`** → Si estamos con la terminal apuntando al archivo que queremos abrir con VSCode, al hacer esto se nos abrirá automáticamente.
- **`code . --profile=NombrePerfil`** → Abre el archivo en el que nos encontramos con el perfil de VSCode que queramos. Personalmente, yo uso un montón los perfiles de VSCode y me resulta super fácil gestionarlos así desde el cmd con Windows 11. Ej: "code . --profile=JavaDev"

## En el propio VSCode
- **`Ctrl + Shift + P`** → Abre el Command Palette de VSCode
- **`Ctrl + P`** → Abre el explorador de archivos de VSCode donde podemos buscar el nombre de su archivo o su extensión. Ej: buscar "index.html" o todos los archivos de python con ".py". Para abrir los archivos solo tenemos que seleccionarlos y hacer enter.
- **`Shift + Alt + F12`** → Muestra todas las referencias de lo que estemos seleccionando. Ej: Una variable, una función...
- **`Ctrl + Shift + Alt`** → Si presionamos todo esto mientras hacemos click seleccionando una variable o función, nos aparecerán las referencias de esta.
- **`Ctrl + B`** → Abre o cierra la "primary side bar" de VSCode que es la que está a la izquierda donde podemos realizar acciones como ver los archivos, crear una carpeta, buscar extensiones...
- **`Ctrl + Shift + V`** → Enseña en otra ventana una versión de "Preview" mostrando cómo se vería el archivo, eso es muy interesante para los que tienen extensión ".md"
- **`Ctrl +  Ñ`** → Aparece la terminal de VSCode <br>
![Puedes ver un ejemplo aquí](https://github.com/CrisCorreaS/trucos-vscode/blob/main/Shortcuts/Videos/terminal.gif)
- **`Ctrl + "+"`** → Aumenta el zoom en VSCode
- **`Ctrl + "-"`** → Disminuye el zoom en VSCode 
- **`Ctrl + "⬆"`** o **`Ctrl + "⬇"`** → Sube o baja el scroll de VSCode sin afectar a donde está el cursor ya que este se mantiene en el mismo sitio. Si solo hacemos `⬆` o `⬇`, el cursor se mueve haciendo que el scroll también, pero si mantenemos pulsado `Ctrl`, solo se mueve el scroll.

## En general el cualquier archivo con extensión .html, .css o .js:
### KeyBoard Shortcuts
- **`Ctrl + Ç`** → Podremos hacer un comentario o comentar el código que hemos seleccionado en cualquiera de esos archivos
- **Fn + F2** → Renombra una variable
- **`(Ctrl + K)+(Ctrl + C)`** → Si pulsamos `Ctrl + K` y seguidamente `Ctrl + C`, podremos hacer lo mismo que con `Ctrl + ç`
  - Si lo hacemos en html nos aparecerá: ``<!--  -->``
  - Si lo hacemos en css nos aparecerá: ``/*  */``
  - Si lo hacemos en js nos aparecerá: ``//``
- **`Ctrl + C`** / **`Ctrl + X`** / **`Ctrl + V`** → Si hacemos `Ctrl + C`, `Ctrl + X` o `Ctrl + V` al final de la línea, se copiará, cortará o pegará (respectivamente), toda la línea, incluido el elemento de la línea y los comentarios que haya.
- **`Ctrl + Shift + K`** → Elimina la línea en la que estamos o las líneas que estamos seleccionando.
- **`Ctrl + A`** → Selecciona todo lo que hayamos marcado
- **`Ctrl + F`** → Abre el buscador de texto para encontrar palabras o expresiones regulares e incluso reemplazarlas por otras
- **`Tab`** → Si seleccionamos parte de un código y hacemos click sobre el tabulador, se le añade un espacio. Esto ayuda a indentar el código.
- **`Tab + Shift`** → Si seleccionamos parte de un código y hacemos `Tab + Shift`, se le quita un espacio. Es la acción inversa a hacer click en `Tab`.
- **`Alt + Z`** → Hace que el código se ajuste al tamaño de la pestaña en la que trabajas y no tengas que hacer scroll horizontal. Por ejemplo: si tienes varios párrafos con un contenido muy grande y tienes que estar constantemente haciendo scroll, al pulsar `Alt + Z`, los párrafos se adaptan a tu pantalla y no tienes que hacer más scroll horizontal. Personalmente, me gusta más cómo funciona "Prettier" porque lo deja más ordenadito <br>
![Puedes ver un ejemplo aquí](https://github.com/CrisCorreaS/trucos-vscode/blob/main/Shortcuts/Videos/scroll-horizontal.gif)
- **`Alt + "⬆"`** o **`Alt + "⬇"`**  → Si seleccionamos un bloque de texto o simplemente dejamos el cursor encima de una línea de texto y pulsamos esas teclas, moverá todo ese texto hacia arriba o hacia abajo. Muy útil para cuando refactorizas código.
- **`Shift + Alt + "⬆"`** o **`Shift + Alt + "⬇"`** → Si seleccionamos un bloque de texto o simplemente dejamos el cursor en una línea de texto y pulsamos esas teclas, hará un copy-paste de ese texto y lo moverá hacia arriba o hacia abajo.
- **`Ctrl + Click Izquierdo`** → Podemos ir a ver donde se originó una variable si la seleccionamos y hacemos ese comando

### Cursor tricks
- **Click en un elemento + `Alt` + más clicks** → Hacer click en un sitio concreto, luego pulsar `Alt` y hacer click en otros sitios (tantos como se quiera), hace que se pueda incluir código y borrarlo en todos los lugares en los que se ha hecho click <br>
![Puedes ver un ejemplo aquí](https://github.com/CrisCorreaS/trucos-vscode/blob/main/Shortcuts/Videos/select-many-elements.gif)
- **Doble click en una palabra + `Ctrl + D`** → Si seleccionamos una palabra al hacer doble click y luego hacemos `Ctrl + D` las veces que queramos, se seleccionarán tantas instancias de esta como hayamos querido. Al hacer esto, el cursor se multiplicará todas las veces que queramos y se pondrá al final de la palabra. Esto es super útil cuando quieres modificar la palabra o las sentencias en las que esté. 
- **Doble click en una palabra + `Ctrl + Shift + L`** → Es igual que el anterior pero esta vez con presionar las teclas una vez, se seleccionarán todas las instancias de la palabra seleccionada y se colocará un cursor al final de cada una de las instancias.
- **Selección haciendo click y manteniendo + `Alt + Shift`** → Cuando hacemos un click, mantenemos pulsado el ratón y usamos las teclas `Alt + Shift`, en vez de hacer una "wrapping selection", hacemos una "box selection" la cual es mucho más fácil de utilizar para según qué casos. [Aquí tienes más información](https://www.youtube.com/watch?v=ONLERMB-DQw)
- **Pulsar el botón central (la ruedita) y mantener** → Es lo mismo que lo anterior, con esto hacemos una "box selection"