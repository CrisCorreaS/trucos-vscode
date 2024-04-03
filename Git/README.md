# Trucos de VSCode al utilizar Git

## En Source Control
### Panel superior
- Si pulsamos la opción **View as a List**, se cambia la vista de los cambios en el repositorio de Git a una lista. Esto significa que, en lugar de ver los cambios en un formato de árbol, como se muestra por defecto, los cambios se presentan en una lista plana. Se puede cambiar la vista nuevamente haciendo otro click en la misma opción.
- Si pulsamos la opción de **Commit**, se hará un commit de todos los cambios que estén en el **Staged Changes** con el mensaje que se haya cubierto en la parte inferior del panel superior.
- Si tenemos la extensión **Git History** tendremos la opción **View History (git log)** donde veremos el historial de logs del repositorio
- Si pulsamos en **Refresh** se refrescará el contenido de nuestro repositorio buscando archivos modificados, borrados, etc. También avisará si ha habido algún nuevo commit en el repositorio de GitHub y nos avisará si eso pasa.
- Si tenemos la extensión **Git Graph** tendremos la opción **View Git Graph (git log)** que será la misma a la de la extensión de Git History
#### **En los tres puntitos**
- **View > Source Control Repositories**
- **View & Sort**
- **Incomming & Outgoing**
- **Pull**
- **Push**
- **Clone**
- **Checkout to...**
- **Fetch**
- **Commit**
- **Changes**
- **Pull, Push**
- **Branch**
- **Remote**
- **Stash**
- **Tag**
- **Show Git Output**

### Panel inferior
- Si en la zona donde aparece **Changes** hacemos click en el símbolo `+` haremos un `git add` de todos los archivos. Si hacemos click en el `+` al lado de un archivo, solo haremos un `git add` de ese archivo en específico.
- Podremos ver todos los archivos que están en el stage en **Staged Changes**, si hacemos click en el símbolo `-` es como si hiciéramos un `git reset` de todos los archivos. Si hacemos click en el `-` al lado de un archivo, solo haremos un `git reset` de ese archivo en específico.
- Tanto en **Changes** como en **Staged Changes**, si hacemos click en "View Changes" podemos ver los cambios que han surgido. En "Staged Changes" podemos ver los cambios entre cómo está el archivo actual en el stage y de cómo estaba en el último commit. En "Changes" podemos ver los cambios entre cómo está el archivo actual en el directorio de trabajo y cómo está en el stage o en el último commit.
- En **Changes** también hay una opción de "Discard Changes" donde elimina los cambios que sucedieron en el directorio de trabajo y se queda con el estado del stage o el del último commit

## En general
- Si en la esquina inferior izquierda hacemos click donde está el nombre de la rama en la que nos situamos, nos aparecerá un pop up de la command palette donde podremos elegir si queremos crear una rama nueva, crear una rama a partir de otra, ver las ramas que hay en nuestro repositorio, cambiar la rama si hacemos click en otra rama y ver las tags que existen e ir a estas.

