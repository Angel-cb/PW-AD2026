## 20 Comandos Git

### Comando
git-add
### Descripción
Agrega el contenido de archivos al índice
### Ejemplo de caso de uso
Después de modificar un archivo se usa para marcarlo como listo para el proximo commit

---

### Comando
git-am
### Descripción
Aplica una serie de parches desde un mailbox
### Ejemplo de caso de uso
Aplicar los cambios desde un archivo .patch a un proyect

---

### Comando
git-archive
### Descripción
Crea un archivo comprimido desde un árbol con nombre
### Ejemplo de caso de uso
Cuando se quiere enviar el código de un proyecto en un .zip sin el historial de Git

---

### Comando
git-backfill
### Descripción
Descarga objetos faltantes en un clon parcial 

### Ejemplo de caso de uso
Si se tiene clonado un repositorio muy grande de forma parcial,lo usas para completar el historial

---

### Comando
git-bisect
### Descripción
Usa busqueda binaria para encontrar el commit que introdujo un error/bug
### Ejemplo de caso de uso
Se usa para que git ayude a encontrar en que commit exacto se rompio

---

### Comando
git-branch
### Descripción
Lista, crea o elimina ramas/branches
### Ejemplo de caso de uso
Cuando no se quiere modificar la rama principal creas una nueva con este comando

---

### Comando
git-bundle
### Descripción
Mover objetos y referencias por archivo
### Ejemplo de caso de uso
Pasar un repositorio a otra computadora sin internet, por ejemplo mediante USB

---

### Comando
git-checkout
### Descripción
Cambiar de rama o restaurar los archivos del árbol de trabajo
### Ejemplo de caso de uso
Si se quiere pasar de una rama a otra para seguir trabajando en ella

---

### Comando
git-cherry-pick
### Descripción
Aplicar los cambios introducidos por algunas confirmaciones existentes
### Ejemplo de caso de uso
Cuando se necesita  traer un cambio especifico de otra rama sin traer todos sus cambios

---

### Comando
git-merge
### Descripción
Une los cambios de una rama con otra
### Ejemplo de caso de uso
Cuando se termina de trabajar en una rama y se quieren pasar los cambios a la rama principal

---

### Comando
git-clean
### Descripción
Elimina los archivos no rastreados del árbol de trabajo
### Ejemplo de caso de uso
Si hay archivos temporales o de prueba, los borra del protecto

---

### Comando
git-clone
### Descripción
Clona un repositorio en un nuevo directorio
### Ejemplo de caso de uso
Descargar un repositorio de GitHub a una computadora

---

### Comando
git-commit
### Descripción
Registrar los cambios en el repositorio
### Ejemplo de caso de uso
Guardar los cambios en el historial del proyecto

---

### Comando
git-init
### Descripción
Crea un repositorio Git vacío o reinicializa uno existente
### Ejemplo de caso de uso
Cuando se empieza un proyecto nuevo y se quiere convertir su carpeta en un repositorio de Git para llevar control de versiones

---

### Comando
git-describe
### Descripción
Asigna a un objeto un nombre legible para humanos basado en una referencia disponible
### Ejemplo de caso de uso
Si se quiere saber que tan cerca esta un commit actual de una version marcada con un tag

---

### Comando
git-diff
### Descripción
Mostrar cambios entre confirmaciones, confirmación y árbol de trabajo, etc
### Ejemplo de caso de uso
Antes de hacer commit, revisa exactamente que lineas se modificaron

---

### Comando
git-fetch
### Descripción
Descargar objetos y referencias desde otro repositorio
### Ejemplo de caso de uso
Revisar si hay cambios nuevos en el repositorio remoto

---

### Comando
git-pull
### Descripción
Obtener e integrar con otro repositorio o una rama local
### Ejemplo de caso de uso
Si un compañero de equipo hace cambios al repositorio y quiero traerlos a mi copia local

---

### Comando
git-push
### Descripción
Actualizar las referencias remotas junto con los objetos asociados
### Ejemplo de caso de uso
Se termino de hacer commit y se quiere subir al repositorio remoto, como GitHub

---

### Comando
git-rm
### Descripción
Elimina archivos del árbol de trabajo y del índice
### Ejemplo de caso de uso
Si se sube un archivo por error, lo elimina y hace que git deje de seguirlo

## Referencias
https://git-scm.com/docs/git#_git_commands
https://docs.github.com/en/get-started/using-git/about-git