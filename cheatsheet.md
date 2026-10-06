# Mi resumen de comandos de Git

## git status
Me permite ver cómo está actualmente mi repositorio. Me dice qué archivos cambiaron, cuáles están preparados para un commit y cuáles todavía no están siendo seguidos por Git.

## git add
Sirve para preparar un archivo y decirle a Git que quiero incluir sus cambios en el siguiente commit.

Ejemplo:
git add archivo.md

También puedo preparar todos los cambios con:
git add .

## git commit
Guarda los cambios que preparé con git add en el historial del repositorio.

Ejemplo:
git commit -m "Agrega información al proyecto"

## git push
Envía a GitHub los commits que hice en mi computadora.

## git pull
Descarga los cambios más recientes que existen en GitHub y los integra a mi repositorio local.

## git log
Muestra el historial de commits que se han realizado.

Puedo verlo de forma resumida con:
git log --oneline

## git diff
Muestra los cambios que hice en mis archivos pero que todavía no he preparado con git add.

## git restore
Sirve para descartar cambios de un archivo y regresar a la versión que estaba guardada en el último commit.

Ejemplo:
git restore archivo.md

## git restore --staged
Sirve para sacar un archivo de la zona de preparación después de haber hecho git add, pero conserva los cambios que hice en el archivo.

Ejemplo:
git restore --staged archivo.md