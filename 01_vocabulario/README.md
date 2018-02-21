## Introducción
Poco a poco vamos aprendiendo más acerca del mundo de la informática, y es por eso que continuando con la primera lección, aquí podrás conocer un poco de vocabulario acerca del trabajo en los Sistemas de Control de Versiones.
##
### Vocabulario de trabajo con SCV
#### ELEMENTOS BÁSICOS
| Palabra | Descripción |
|--|--|
| **Repositorio** |Almacena información y suele tener estructura de árbol
|**Servidor** |Dónde se encuentra alojado el repositorio
|**Working Copy / Working Set** | Copia local donde el desarrollador trabaja
|**Trunk / Main / master** | Localización del repositorio que contiene la rama principal
##
#### OPERACIONES BÁSICAS
| Palabra | Descripción |
|--|--|
| **Add** |Añande un archivo
|**Revisión** | Versión de un archivo/directorio
|**Head** |Última versión del repositorio
|**Check out** | Creación de una copia de trabajo que rastrea un repositorio
|**Check in / Commits** | Envia los cambios y cambia la versión de los archivos
|**Mensaje Check in / log** | Todo 'Check', tiene un mensaje que describe la finalidad del cambio, o de aviso del error
|**Log**|Permite ver/revisar la lista de cambios en los archivos que se encuentran en un repositorio
|**Update / Syncronize / fetch&pull**|Sincroniza la copia de trabajo con la última versión que exista del repositorio
|**Revert / Reset**|Permite deshacer los cambios que se realicen en la copia de trabajo, y deja el archivo en la última versión que se conozca
##
#### OPERACIONES AVANZADAS
| Palabra | Descripción |
|--|--|
| **Branching** |Permite crear una copia de un archivo o directorio, y desarrollar en paralelo otra rama diferente a la original, sin variar la original
|**Diff / Change / Delta** |Permite encontrar las diferencias entre dos versiones, y generar un parche que permita pasar de una versión a otra
|**Merge / Patch** | Aplica los cambios de un archivo a otro, normalmente se utiliza para mezclar diversos branches
|**Conflict** | Problema que surge cuando varios desarrolladores modifican el mismo recurso y esos cambios se solapan
