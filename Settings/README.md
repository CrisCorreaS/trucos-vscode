# SETTINGS VSCODE
## Generales
- **Espacios de Indentación** → Según el Standard Web y la [Guía de Estilos de Google](https://google.github.io/styleguide/htmlcssguide.html#Indentation), deberían de haber 2 espacios de indentación, no 4. Para establecer los espacios de indentación en 2, podemos hacerlo de dos formas:
  - Si queremos establecerlos para siempre en 2: Tenemos que darle a la ruedita inferior izquierda y elegir la opción "Settings" (o hacer un `Ctrl + ","`). En la barra de "Search Settings" escribimos "Tab Size", buscamos la opción "Editor: Tab Size → The number of spaces a tab is equal to. This setting is overridden based on the file contents when Editor: Detect Indentation is on" y escribimos el número de espacio de indentación deseado (2).
  - Si en el proyecto actual los queremos establecer en 2 pero luego en el resto de proyectos preferimos los espacios de otra manera: tenemos que ir a la barra inferior de VSCode y buscar el apartado "Spaces", hacemos click sobre este y veremos que en la barra del buscador aparecerá la opción "Indent Using Spaces". Hacemos click en esa opción y observaremos un desplegable con varios valores numéricos, ahí tendremos que seleccionar el número "2" y podremos ver que en la barra inferior de VSCode ahora pone "Spaces:2"

- **Sticky Scroll para mejorar el explorador de carpetas** → Es una característica que ayuda a los desarrolladores a navegar a través de archivos de código grandes o bases de código desconocidas. Puede ser especialmente útil cuando es difícil rastrear en qué lugar del código te encuentras.
  - Para establecer el sticky scroll, tenemos que darle a la ruedita inferior izquierda y elegir la opción "Settings" (o hacer un `Ctrl + ","`). En la barra de "Search Settings" escribimos "Sticky Scroll", buscamos la opción "Workbench › Tree: Enable Sticky Scroll" y hacemos que se marque un check en "Controls whether sticky scrolling is enabled in trees."

- **Linked Editing** → Es una característica que permite actualizar automáticamente los símbolos relacionados mientras se edita el código. Por ejemplo, si trabajamos con etiquetas HTML y cambiamos la etiqueta de apertura, la etiqueta de cierre correspondiente también se actualizará para coincidir con el cambio.
  - Para establecer linked editing, tenemos que darle a la ruedita inferior izquierda y elegir la opción "Settings" (o hacer un `Ctrl + ","`). En la barra de "Search Settings" escribimos "Linked Editing", buscamos la opción "Editor: LinkedEditing" y hacemos que se marque un check en "Controls whether the editor has linked editing enabled."

- **Bracket Pair Colorization** → Es una característica que ayuda a identificar visualmente los pares de corchetes correspondientes en el código fuente. Cuando esta característica está activada, cada par de corchetes se muestra con diferentes colores, lo cual facilita la lectura y comprensión del código, especialmente cuando se trabaja con estructuras de código profundamente anidadas
  - Para establecer bracket pair colorization, tenemos que darle a la ruedita inferior izquierda y elegir la opción "Settings" (o hacer un `Ctrl + ","`). En la barra de "Search Settings" escribimos "Bracket Pair Colorization", buscamos la opción "Editor › Bracket Pair Colorization" y hacemos que se marque un check en "Controls whether bracket pair colorization is enabled or not."

- **Bracket Pairs** → Es una característica de colorización de pares de corchetes que ayuda a los desarrolladores a distinguir visualmente los pares de corchetes abiertos y cerrados en el código.
  - Para establecer bracket pairs, tenemos que darle a la ruedita inferior izquierda y elegir la opción "Settings" (o hacer un `Ctrl + ","`). En la barra de "Search Settings" escribimos "Bracket Pairs", buscamos la opción "Editor › Guides: Bracket Pairs" y hacemos que se elija la opción "true" en "Controls whether bracket pair guides are enabled or not."

- **Cursor Blinking** → Es una característica que te permite personalizar la forma en que el cursor de texto se comporta visualmente en el editor de VSCode. Cuando el cursor parpadea, cambia su aspecto visual para indicar su posición en el texto. La opción "Cursor Blinking Expand" tiene varios modos, cada uno con un comportamiento diferente entre los que destacan: la opción por defecto (blink) donde el cursor parpadea entre su posición normal y una posición expandida y mi opción favorita (expand)donde el cursor también parpadea pero con un efecto más smooth.
  - Para establecer cursor blinking, tenemos que darle a la ruedita inferior izquierda y elegir la opción "Settings" (o hacer un `Ctrl + ","`). En la barra de "Search Settings" escribimos "Cursor Blinking", buscamos la opción "Editor › Cursor Blinking" y hacemos que se marque la opción "expand" en "Control the cursor animation style." y en "Terminal › Integrated: Cursor Blinking" marcamos con un check la opción "Controls whether the terminal cursor blinks."

- **Code Lens** → Son características de Visual Studio Code que proporcionan información contextual sobre el código directamente en el editor, facilitando la navegación y comprensión del código. Las **References Code Lens**, muestran un recuento en línea de las referencias para clases, interfaces, métodos, propiedades y objetos exportados. Al hacer clic en el recuento de referencias, puedes navegar rápidamente a través de una lista de todas las referencias al elemento de código. Las **Implementations Code Lens** muestran el número de implementadores de una interfaz y funcionan igual que las otras.
  - Para establecer code lens, tenemos que darle a la ruedita inferior izquierda y elegir la opción "Settings" (o hacer un `Ctrl + ","`). En la barra de "Search Settings" escribimos "Code Lens", buscamos las siguientes opciones:
      -  "Editor › Code Lens" y hacemos que se marque con un check la opción "Controls whether the editor shows CodeLens." para poder habilitar cualquier tipo de Code Lens.
   - Para JavaScript:
      -  "JavaScript › References Code Lens: Enabled" y hacemos que se marque con un check la opción "Enable/disable references CodeLens in JavaScript files."
      -  "JavaScript › References Code Lens: Show On All Functions" y hacemos que se marque con un check la opción "Enable/disable references CodeLens on all functions in JavaScript files."
   - Para TypeScript:
      -  "TypeScript › Implementations Code Lens: Enabled" y hacemos que se marque con un check la opción "Enable/disable implementations CodeLens. This CodeLens shows the implementers of an interface."
      -  "TypeScript › Implementations Code Lens: Show On Interface Methods" y hacemos que se marque con un check la opción "Enable/disable implementations CodeLens on interface methods."
      -  "TypeScript › References Code Lens: Enabled" y hacemos que se marque con un check la opción "Enable/disable references CodeLens in TypeScript files."
      -  "TypeScript › References Code Lens: Show On All Functions" y hacemos que se marque con un check la opción "Enable/disable references CodeLens on all functions in TypeScript files."

- **File Nesting** → Es una característica que permite agrupar visualmente archivos relacionados bajo un "archivo raíz" en el mismo directorio, ayudando a reducir el desorden visual en el explorador de archivos del editor. Por ejemplo: en una app simple de React, en "package.json" se anida "package-lock.json" por defecto.
  - Para establecer file nesting, tenemos que darle a la ruedita inferior izquierda y elegir la opción "Settings" (o hacer un `Ctrl + ","`). En la barra de "Search Settings" escribimos "File Nesting", buscamos la opción "Explorer › File Nesting: Expand" y hacemos que se marque un check en "Controls whether file nests are automatically expanded. Explorer › File Nesting: Enabled must be set for this to take effect."
  - Para configurar cómo queremos que estén animados estos archivos, tenemos que ir hacia abajo y buscar una tabla que por defecto aparece así:
    | Item| Value|
    | ----- | ---- |
    | *.ts | ${capture}.js |
    | *.js | ${capture}.js.map, ${capture}.min.js, ${capture}.d.ts |
    | *.jsx | ${capture}.js |
    | *.tsx | ${capture}.js |
    | tsconfig.json | tsconfig.*.json |
    | package.json | package-lock.json, yarn.lock, pnpm-lock.yaml, bun.lockb |

    Y por ahora mi sugerencia es dejarlo así:
    | Item| Value|
    | ----- | ---- |
    | *.ts | ${capture}.js |
    | *.js | ${capture}.js.map, ${capture}.min.js, ${capture}.d.ts |
    | *.jsx | ${capture}.js |
    | *.tsx | ${capture}.js |
    | tsconfig.json | tsconfig.*.json |
    | package.json | package-lock.json, yarn.lock, pnpm-lock.yaml, bun.lockb, .eslintrc.*, .gitignore, jsconfig.json, next.config.mjs, postcss.config.js, prettier.config.js, tailwind.config.js, vite.config.js |
    | .env | .env* |
    | .gitignore | .gitattributes, .gitmodules, .gitmessage, .mailmap, .git-blame* |
    | README.md | LICENSE, AUTHORS, CHANGELOG.md, CODE_OF_CONDUCT.md, CODEOWNERS, CONTRIBUTING.md |
    | pom.xml | mvnw* |
 
  - Un ejemplo del resultado en un proyecto de React con Vite y Tailwinds:

    ![Ejemplo de cómo quedan anidados los archivos](https://github.com/CrisCorreaS/trucos-vscode/blob/main/Settings/img/img-file-nesting1.png) ➡
    ![Ejemplo de cómo quedan anidados los archivos](https://github.com/CrisCorreaS/trucos-vscode/blob/main/Settings/img/img-file-nesting2.png)

## Para Java
- **Java: Open Java Formatter Settings with Preview** → Sirve para editar y previsualizar los ajustes del formateador de Java. Esto permite a los usuarios personalizar cómo se formatea el código Java en vscode, ajustando aspectos como el estilo de sangría, el espaciado entre líneas, y más.
  - Para establecer un formateado para Java, tenemos que ir a la command palette con `Ctrl + Shift + P` y buscar "Java: Open Java Formatter Settings with Preview". Nos aparecerá un popup preguntando si queremos crear el archivo "java-formatter.xml" y le tenemos que dar a aceptar. Ahora ya podremos editar los siguientes parámetros: Indentation, Blank Lines, Comment, Insert Line, Whitespace y Wrapping.
  - Si queremos establecer un estilo de formateo específico como el estilo de Google, podemos ir al **settings.json** (command palette y buscando "Preferences: Open Workspace Settings (JSON)") y añadir las siguientes líneas:
  ```
    "java.format.settings.url": "https://raw.githubusercontent.com/google/styleguide/gh-pages/eclipse-java-google-style.xml",
    "java.format.settings.profile": "GoogleStyle",
  ```

## Creación de snippets
Para ver los snippets que hay podemos ir al Command Palette, escribir "Snippets" y seleccionar la opción "Snippets: Insert Snippet". Basado en el tipo de archivo que tengas abierto, aparecerán una serie de snippets diferentes (ej: JavaScript Language Basics) donde podemos ver los snippets y sus abreviaturas para llamarlos.


Si queremos crear un snippet, tenemos que volver al Command Palette, escribir "Snippets" y esta vez seleccionar la opción "Snippets: Configure User Snippets". A continuación tendremos que seleccionar el lenguaje de programación para el que vamos a crear el snippet y se nos abrirá un archivo json con unas instrucciones de cómo crear un snippet. Los snippets siguen esta estructura:

```
{
  // Comentarios de la explicación

  "Nombre del snippet": {
    "prefix": "prefijo para llamar al snippet",
    "body": ["cuerpo del snippet"],
    "description": "descripción del snippet"
  }
}
```
Un ejemplo de un snippet para "print f strings" de Python sería el siguiente:

```
{
  // Comentarios de la explicación

  "F print": {
    "prefix": "fprint",
    "body": [
      "print(f'Hello {name}')"
    ],
    "description": "Print f strings"
  }
}
```
Y gracias a eso si ahora en un archivo .py escribimos el prefijo del nuevo snippet, **fprint**, nos aparecería el snippet que hemos creado.

## Content assistant para JavaScript o TypeScript
Aunque suene contraintuitivo, TypeScript nos ayuda bastante con el tipo de content assist que ofrece VSCode tanto para JavaScript como para TypeScript, por lo que es una buena práctica instalarlo aunque únicamente estemos en un proyecto de JavaScript Vanilla.


A continuación veremos como instalar globalmente TypeScript en nuestro proyecto:

1. Comprobamos que tengamos instalado TypeScript escribiendo en la consola de vscode `tsc --version`
2. Si no lo tenemos instalado, escribimos `npm i -g typescript`
3. Una vez instalado, tendremos TypeScript globalmente en nuestro sistema. Ahora, volvemos al paso 1 para ver si todo ha salido bien y nos aparece la versión de TypeScript que tenemos
4. Al tener instalado TypeScript de forma global, vscode puede buscar por definiciones de tipos en los archivos y te ayuda a no tener typos. Ej: si en vez de poner "document", ponemos "doccument", aparecerá que el tipo de este es "any", mientras que si lo escribimos bien, el tipo es "Document". 
5. Ahora solo nos falta instalar las definiciones de tipos para Node como dependencias de desarrollo, con el comando `npm i -D @types/node`. Estas definiciones de tipos son proporcionadas por el paquete **node_modules/@types/node**, que contiene las definiciones de tipos para los módulos y APIs de Node

Ahora si hacemos hover sobre un método, tendremos una asistencia más completa y nos dirá el tipo de parámetros que necesita y lo que nos va a devolver. Ej: para **document.getElementById('ejemplo')** al hacer hover nos aparecerá **(method) Document.getElementById(elementId: string): HTMLElement | null** lo cual nos informa que el parámetro que tenemos que introducir en el método es un String y que nos va a devolver un HTMLElement o null.
También tendremos asistencia con por ejemplo métodos como addEventListener donde nos ayudará con el tipo de evento que queremos capturar dándonos una lista de todos. Esto es muy interesante porque por defecto no nos aparece ese tipo de ayuda.
Al instalar **@types/node** como una dependencia de desarrollo, nos aseguramos de que nuestro proyecto tenga acceso a definiciones de tipos, mejorando la calidad del código y facilitando el desarrollo en proyectos que utilizan Node