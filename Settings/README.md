# SETTINGS VSCODE
- **Espacios de Indentación** -> Según el Standard Web y la [Guía de Estilos de Google](https://google.github.io/styleguide/htmlcssguide.html#Indentation), deberían de haber 2 espacios de indentación, no 4. Para establecer los espacios de indentación en 2, podemos hacerlo de dos formas:
  - Si queremos establecerlos para siempre en 2: Tenemos que darle a la ruedita inferior izquierda y elegir la opción "Settings" (o hacer un `Ctrl+","`). En la barra de "Search Settings" escribimos "Tab Size", buscamos la opción "Editor: Tab Size -> The number of spaces a tab is equal to. This setting is overridden based on the file contents when Editor: Detect Indentation is on" y escribimos el número de espacio de indentación deseado (2).
  - Si en el proyecto actual los queremos establecer en 2 pero luego en el resto de proyectos preferimos los espacios de otra manera: tenemos que ir a la barra inferior de VSCode y buscar el apartado "Spaces", hacemos click sobre este y veremos que en la barra del buscador aparecerá la opción "Indent Using Spaces". Hacemos click en esa opción y observaremos un desplegable con varios valores numéricos, ahí tendremos que seleccionar el número "2" y podremos ver que en la barra inferior de VSCode ahora pone "Spaces:2"

- **Sticky Scroll para mejorar el explorador de carpetas** -> Es una característica que ayuda a los desarrolladores a navegar a través de archivos de código grandes o bases de código desconocidas. Puede ser especialmente útil cuando es difícil rastrear en qué lugar del código te encuentras.
  - Para establecer el sticky scroll, tenemos que darle a la ruedita inferior izquierda y elegir la opción "Settings" (o hacer un `Ctrl+","`). En la barra de "Search Settings" escribimos "Sticky Scroll", buscamos la opción "Workbench › Tree: Enable Sticky Scroll" y hacemos que se marque un chech en "Controls whether sticky scrolling is enabled in trees."

- **Linked Editing** -> Es una característica que permite actualizar automáticamente los símbolos relacionados mientras se edita el código. Por ejemplo, si trabajamos con etiquetas HTML y cambiamos la etiqueta de apertura, la etiqueta de cierre correspondiente también se actualizará para coincidir con el cambio.
  - Para establecer linked editing, tenemos que darle a la ruedita inferior izquierda y elegir la opción "Settings" (o hacer un `Ctrl+","`). En la barra de "Search Settings" escribimos "Linked Editing", buscamos la opción "Editor: LinkedEditing" y hacemos que se marque un chech en "Controls whether the editor has linked editing enabled."

- **Bracket Pair Colorization** -> Es una característica que ayuda a identificar visualmente los pares de corchetes correspondientes en el código fuente. Cuando esta característica está activada, cada par de corchetes se muestra con diferentes colores, lo cual facilita la lectura y comprensión del código, especialmente cuando se trabaja con estructuras de código profundamente anidadas
  - Para establecer bracket pair colorization, tenemos que darle a la ruedita inferior izquierda y elegir la opción "Settings" (o hacer un `Ctrl+","`). En la barra de "Search Settings" escribimos "Bracket Pair Colorization", buscamos la opción "Editor › Bracket Pair Colorization" y hacemos que se marque un chech en "Controls whether bracket pair colorization is enabled or not."

- **Bracket Pairs** -> Es una característica de colorización de pares de corchetes que ayuda a los desarrolladores a distinguir visualmente los pares de corchetes abiertos y cerrados en el código.
  - Para establecer bracket pairs, tenemos que darle a la ruedita inferior izquierda y elegir la opción "Settings" (o hacer un `Ctrl+","`). En la barra de "Search Settings" escribimos "Bracket Pairs", buscamos la opción "Editor › Guides: Bracket Pairs" y hacemos que se elija la opción "true" en "Controls whether bracket pair guides are enabled or not."

- **Sticky Scroll** -> Es una característica que permite mantener el alcance actual visible en la parte superior del editor mientras se desplaza por el código. Por ejemplo saber en qué función estás.
  - Para establecer sticky scroll, tenemos que darle a la ruedita inferior izquierda y elegir la opción "Settings" (o hacer un `Ctrl+","`). En la barra de "Search Settings" escribimos "Sticky Scroll", buscamos la opción "Editor › Sticky Scroll" y hacemos que se marque un check en "Shows the nested current scopes during the scroll at the top of the editor."

- **File Nesting** -> Es una característica que permite agrupar visualmente archivos relacionados bajo un "archivo raíz" en el mismo directorio, ayudando a reducir el desorden visual en el explorador de archivos del editor. Por ejeplo: en una app simple de React, en "package.json" se anida "package-lock.json" por defecto.
  - Para establecer file nesting, tenemos que darle a la ruedita inferior izquierda y elegir la opción "Settings" (o hacer un `Ctrl+","`). En la barra de "Search Settings" escribimos "File Nesting", buscamos la opción "Explorer › File Nesting: Expand" y hacemos que se marque un check en "Controls whether file nests are automatically expanded. Explorer › File Nesting: Enabled must be set for this to take effect."
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
    
