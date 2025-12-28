Para crear un nuevo repositorio en GitHub desde Visual Studio Code (VS Code), sigue estos pasos:

Antes de nada y visto el funcionamiento de VSCODE, cabe decir que creemos más idóneo hacer el git init que hacerlo desde dentro del propio editor. A pesar que es posible, las continuas mejoras y cambios del editor y de la extensión hacen cambios significativos en los menús y convierten el intento en una aventura por encontrar estás órdenes de menú. Aún así, procedemos a enunciar los pasos para hacerlo por si, a pesar de la advertencia nos empeñamos en el intento.

Primero, asegúrate de tener instalada la extensión "GitHub Pull Requests and Issues" en VS Code, ya que facilita la integración con GitHub.
 Luego, inicia sesión en tu cuenta de GitHub desde VS Code para autenticarte.

Una vez autenticado, puedes crear un nuevo repositorio directamente desde VS Code. Abre la paleta de comandos con Ctrl + Shift + P y escribe "Git: Create Repository" o busca la opción relacionada con la creación de un repositorio. Esto inicializará un repositorio local en la carpeta actual.

Después de inicializar el repositorio local, puedes publicarlo en GitHub. Desde la paleta de comandos, selecciona "Git: Publish Repository".
 Si el repositorio aún no existe en GitHub, este proceso creará automáticamente el repositorio remoto en tu cuenta de GitHub.
 Durante este proceso, se te pedirá que especifiques el nombre del repositorio, si será público o privado, y si deseas crear un archivo README inicial.

Alternativamente, puedes crear el repositorio en GitHub primero desde el sitio web de GitHub (haciendo clic en "New repository") y luego clonarlo en VS Code usando la opción "Git: Clone" desde la paleta de comandos.
 Esto es útil si prefieres configurar el repositorio remoto antes de trabajar con él localmente.

En resumen, puedes crear un repositorio desde VS Code directamente mediante la publicación de un repositorio local existente, lo cual crea automáticamente el repositorio remoto en GitHub.

**Existe un menú en Visual Studio Code que te permite acceder a la acción para crear un repositorio**, aunque el nombre exacto puede variar según la versión y la configuración.

Puedes encontrar la opción en la barra de menús:

Ve a Git > Crear repositorio de Git (en inglés: Git > Create Git Repository).
Al seleccionarlo, VS Code te guiará para inicializar un repositorio local y, opcionalmente, publicarlo directamente en GitHub.
Además, también puedes acceder a esta funcionalidad desde:

La paleta de comandos (Ctrl+Shift+P) buscando "Git: Initialize Repository" o "Git: Create Repository".
La vista de Control de Código Fuente (icono de ramificación en la barra lateral), donde puedes hacer clic en "Initialize Repository".