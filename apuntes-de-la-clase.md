
##  Se agrega informacion de como podemos configurar nuestro git con tokens
[Nueva exigencia de autenticación por token en Git ¿qué es y qué debo hacer?](https://www.aluracursos.com/blog/exigendia-autenticacion-por-token)

---
>[!WARNING] Buenas prácticas
>Al crear archivos se debe seguir estar reglas:
> 1. no se debe poner carteres especiales /#&$(
> 2. los nombre no puede ir guion abajo hola_como_estas.txt 
> 3. los archivos son todos con guion medio , ejemplo: hola-mi-archivo.txt
> 4. no utiliza espacios en blanco los archivos: hola mi archivo.txt
---
## COMANDOS DE GIT

---

## `git init`
Inicializa un nuevo repositorio Git en el directorio actual.

---

## `git clone`
Clona un repositorio Git existente desde una URL.

`git clone <repositorio> <mi-proyecto-clone>`: Clona el repositorio `repositorio` en el directorio `mi-proyecto-clone.

`git clone -branch new_feature <repositorio>`: Clona el repositorio `repositorio` en la rama `new_feature`.

[mas configuraciones de git clone](https://git-scm.com/docs/git-clone)

---

## `git add`
Agrega archivos al área de preparación (staging area).

---

## `git commit`
Guarda los cambios en el repositorio local.

---

## `git push`
Envía los commits desde el repositorio local a un repositorio remoto.

---

## `git pull`
Obtiene los cambios desde un repositorio remoto y los fusiona con el repositorio local.

---

## `git switch`
Cambia entre ramas.
`git switch <nombre-rama>`: Cambia a la rama `<nombre-rama>`.

---

## `git branch`
Crea, lista o elimina ramas.

---

## `git checkout`
Cambia entre ramas o restaura archivos de versiones anteriores.

`git checkout -b <nombre-rama>`: Crea una nueva rama llamada `<nombre-rama> `


---

## `git merge`
Fusiona los cambios de una rama en otra.

---

## `git log`
Muestra el historial de commits.  

`git log --oneline` : para ver el log mar resumido, para ver los commits y los hash.

`git log -p`: para ver el log con el código de cada commit.

`git log --author="user_name"`: para ver los commits de un usuario en particular.

`git log --since=1.month.ago --until=1.day.ago`: para ver los commits de los últimos 30 días.

`git log --pretty="format:%h %s"`: para ver el log con el hash y el mensaje de cada commit.

[git log cheatsheet](https://devhints.io/git-log-format)

---

## `git status`
Muestra el estado del repositorio de trabajo.

---

## `git config --global`
Configura opciones globales para el usuario actual.

---

## `git remote`
Gestiona las conexiones con repositorios remotos.

---

## `git fetch`
Obtiene los últimos commits de un repositorio remoto sin fusionar.

---

## `git diff`
Muestra las diferencias entre dos versiones de un archivo.

`git diff <nombre-archivo>`: para ver las diferencias de un archivo en particular.

---

## `git restore`
Restaura un archivo a una versión anterior.

`git restore --source <hash> <nombre-archivo>`: para restaurar un archivo a una versión específica.

[nuevos comandos de git restore y git switch](https://www.aluracursos.com/blog/git-y-los-nuevos-comandos)