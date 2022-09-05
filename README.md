1) Git es un sistema de control de versiones (principalmente utilizado en el desarrollo de software). Este fue creado por Linus Torvalds en 2007, ante la necesidad de tener una manera facil para llevar un orden en las versiones de un software desarrollado.

2) Github es una plataforma online en donde se alojan repositorios de código cuyas versiones son controladas gracias al sistema de control de Git.

3) Un archivo en git puede tener 4 estados posibles:

-Untracked o sin registrar: Significa que el archivo solo existe de manera local y no esta preparado en el staging area, ni subido al repositorio remoto.

-Added o añadido: Significa que el archivo local ya ha sido añadido al staging area, pero no subido.

-Subido: Cuando el archivo que esta en el staging area pasa a ser parte del repositorio remoto.

-Modified o modificado: Significa que un archivo que ya esta en el repositorio, fue modificado localmente y los cambios aun no fueron subidos.

4) Sistema de versionado local: Cada usuario trabaja con sus archivos localmente, en su base de datos local.

5) Sistema de versionado centralizado: Se aloja en un servidor remoto una base de datos con todos los archivos del proyecto. Los contribuidores pueden descargar estos archivos para trabajarlos localmente.

6) Sistema de versionado distribuido: Se aloja en un servidor remoto la base de datos con todos los archivos. A su vez, cada usuario tiene una copia identica de esa base de datos de manera local, para poder ir trabajando todos los archivos de manera local tambien. Al terminar, estos cambios se suben al servidor remoto y se actualizan.

7)
-git status: Muestra el estado de los archivos; si estan o no registrados,  si estan añadidos o no al staging area, o si estan modificados.

-git add: Añade los archivos cuyo nombre sea especificado luego del comando al staging area, preparandolos para subir.

-git add .: Añade todos los archivos del directorio para añadir al staging area.

-git commit -m: Añade un "comentario" a la nueva versión que se subira. Una especie de aviso o descripción de lo realizado en la nueva versión.

-git log: Muestra un registro de todos los commits de las versiones subidas al repositorio.

-git push: Sube o "empuja" los archivos del staging area al repositorio remoto.

14) Los archivos README.md se utilizan para informar a los visitantes de un proyecto sobre:
-Que hace el proyecto.
-El propopsito del proyecto.
-Quienes mantienen el proyecto.
-Donde pueden recibir ayuda los usuarios del proyecto.