# Trucos de VSCode al utilizar Git

## En Source Control
### Panel superior
- Si pulsamos la opción **View as a List**, se cambia la vista de los cambios en el repositorio de Git a una lista. Esto significa que, en lugar de ver los cambios en un formato de árbol, como se muestra por defecto, los cambios se presentan en una lista plana. Se puede cambiar la vista nuevamente haciendo otro click en la misma opción.
- Si pulsamos la opción de **Commit**, se hará un commit de todos los cambios que estén en el **Staged Changes** con el mensaje que se haya cubierto en la parte inferior del panel superior.
- Si tenemos la extensión **Git History** tendremos la opción **View History (git log)** donde veremos el historial de logs del repositorio
- Si pulsamos en **Refresh** se refrescará el contenido de nuestro repositorio buscando archivos modificados, borrados, etc. También avisará si ha habido algún nuevo commit en el repositorio de GitHub y nos avisará si eso pasa.
- Si tenemos la extensión **Git Graph** tendremos la opción **View Git Graph (git log)** que será la misma a la de la extensión de Git History
#### **En los tres puntitos**
- **View > Source Control Repositories** → Esta opción te permite ver y gestionar múltiples repositorios Git dentro de VSCode. Es útil cuando trabajas con varios proyectos o múltiples ramas dentro de un proyecto
- **View & Sort** → Permite personalizar la vista de los repositorios y ordenarlos según tus preferencias. Esto puede incluir la ordenación por nombre, fecha de última modificación, etc.
- **Incomming & Outgoing** → Muestra las diferencias entre tu repositorio local y el repositorio remoto. Las "incoming" son los cambios que están en el repositorio remoto pero aún no se han aplicado a tu repositorio local, mientras que las "outgoing" son los cambios que has hecho localmente pero aún no se han subido al repositorio remoto
- **Pull** → Sincroniza tu repositorio local con el repositorio remoto, descargando los cambios más recientes del repositorio remoto y aplicándolos a tu repositorio local. Es equivalente a hacer un `git pull`
- **Push** → Sube los cambios que has hecho en tu repositorio local al repositorio remoto. Esto es útil para compartir tus cambios con otros colaboradores. Es equivalente a hacer un `git push`
- **Clone** → Permite clonar un repositorio remoto a tu máquina local. Esto es el primer paso para trabajar con un proyecto existente alojado en un repositorio remoto. Es equivalente a hacer un `git clone`
- **Checkout to...** → Te permite cambiar a una rama o etiqueta diferente dentro de tu repositorio. Es útil para trabajar en diferentes versiones del código o para cambiar entre características en desarrollo. Es equivalente a hacer un `git checkout nombreRama`
- **Fetch** →  Descarga los cambios del repositorio remoto sin aplicarlos automáticamente a tu repositorio local. Esto es útil para revisar los cambios antes de fusionarlos. Es equivalente a hacer un `git fetch nombreRama`
- **Commit** → Registra los cambios que has hecho en tu repositorio local en un nuevo commit. Esto es un paso crucial en el flujo de trabajo de Git, ya que permite guardar tus cambios de manera segura. Te permite trabajar con este comando más fácilmente
- **Changes** → Muestra los cambios que has hecho en tu repositorio local. Esto incluye los cambios que aún no se han confirmado (commit)
- **Pull, Push** → Combina las acciones de "Pull" y "Push", sincronizando tu repositorio local con el repositorio remoto en un solo paso. Esto es útil para actualizar rápidamente tu repositorio local con los últimos cambios y subir tus cambios al repositorio remoto. Te permite trabajar con estos comandos en mayor medida.
- **Branch** → Te permite crear, eliminar y gestionar ramas dentro de tu repositorio. Las ramas son una forma de trabajar en diferentes versiones del código sin afectar la versión principal 
- **Remote** → Gestiona los repositorios remotos asociados con tu repositorio local. Esto incluye la adición, eliminación y configuración de repositorios remotos
- **Stash** → Permite organizar y hacer acciones sobre los cambios temporalmente guardados que no deseas confirmar en un commit. Esto es útil para cambiar de rama sin perder tus cambios actuales. Te permite trabajar con varias opciones del stash.
- **Tag** → Permite gestionar etiquetas para marcar puntos específicos en la historia de tu repositorio, como versiones importantes
- **Show Git Output** → Muestra la salida de los comandos de Git ejecutados dentro de VSCode. Esto es útil para depurar problemas o entender mejor lo que está sucediendo detrás de escena 

### Panel inferior
- Si en la zona donde aparece **Changes** hacemos click en el símbolo `+` haremos un `git add` de todos los archivos. Si hacemos click en el `+` al lado de un archivo, solo haremos un `git add` de ese archivo en específico.
- Podremos ver todos los archivos que están en el stage en **Staged Changes**, si hacemos click en el símbolo `-` es como si hiciéramos un `git reset` de todos los archivos. Si hacemos click en el `-` al lado de un archivo, solo haremos un `git reset` de ese archivo en específico.
- Tanto en **Changes** como en **Staged Changes**, si hacemos click en "View Changes" podemos ver los cambios que han surgido. En "Staged Changes" podemos ver los cambios entre cómo está el archivo actual en el stage y de cómo estaba en el último commit. En "Changes" podemos ver los cambios entre cómo está el archivo actual en el directorio de trabajo y cómo está en el stage o en el último commit.
- En **Changes** también hay una opción de "Discard Changes" donde elimina los cambios que sucedieron en el directorio de trabajo y se queda con el estado del stage o el del último commit

## En general
- Si en la esquina inferior izquierda hacemos click donde está el nombre de la rama en la que nos situamos, nos aparecerá un pop up de la command palette donde podremos elegir si queremos crear una rama nueva, crear una rama a partir de otra, ver las ramas que hay en nuestro repositorio, cambiar la rama si hacemos click en otra rama y ver las tags que existen e ir a estas.

