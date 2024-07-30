# Modulo 5 - trabajando con git

## 1. ¿Qué es Git?

Git es un sistema de control de versiones distribuido, diseñado para manejar desde proyectos pequeños hasta muy grandes con velocidad y eficiencia. Permite que múltiples desarrolladores trabajen en el mismo proyecto de manera coordinada, gestionando las modificaciones sobre los archivos del proyecto y preservando un historial completo de todas las versiones y cambios.

## 2. ¿Cuál es el propósito del comando git init en Git?

El comando ```git init``` se utiliza para crear un nuevo repositorio Git. Al ejecutarlo en un directorio, se inicializa un repositorio vacío con una nueva subcarpeta llamada ```.git``` que contiene todos los archivos de configuración y estructura necesarios para el manejo de las versiones del proyecto.

## 3. ¿Qué representa una rama en Git y cómo se utiliza?

Una rama en Git representa una línea independiente de desarrollo. Permite a los desarrolladores trabajar en características, correcciones o experimentos en paralelo al desarrollo principal sin afectar la rama principal (comúnmente llamada master o main). Las ramas se utilizan para desarrollar funcionalidades aisladas y luego se pueden fusionar de nuevo en la rama principal una vez que el trabajo está completo y probado.

## 4. ¿Cómo puedo determinar en qué rama estoy actualmente en Git?
Para determinar en qué rama te encuentras actualmente en Git, puedes utilizar el comando:
```
git branch
```
Este comando listará todas las ramas del repositorio y marcará con un asterisco la rama en la que te encuentras actualmente.

## 5. ¿Quién es la persona responsable de la creación de Git y cuándo fue desarrollado?

Git fue creado por Linus Torvalds, el mismo creador del sistema operativo Linux. Fue desarrollado en 2005 como una herramienta para ayudar en la gestión del desarrollo del kernel de Linux, motivado por la necesidad de un sistema de control de versiones distribuido, eficiente y rápido.

## 6. ¿Cuáles son algunos de los comandos esenciales de Git y para qué se utilizan?

Algunos de los comandos esenciales de Git incluyen:

•	```git clone```: Clona un repositorio existente.
•	```git add```: Añade archivos al área de preparación (staging) para que sean incluidos en el próximo commit.
•	```git commit```: Realiza un commit de los archivos que están en el área de preparación, guardando los cambios en el repositorio.
•	```git push```: Envía los cambios locales a un repositorio remoto.
•	```git pull```: Actualiza el repositorio local con los cambios del repositorio remoto.
•	```git merge```: Fusiona los cambios de una rama a otra.
•	```git checkout```: Cambia de una rama a otra o restaura archivos del repositorio.

## 7. ¿Puedes mencionar algunos de los repositorios de Git más reconocidos y utilizados en la actualidad?

Algunos de los repositorios de Git más reconocidos y utilizados incluyen:
•	Linux Kernel: El repositorio de desarrollo del kernel de Linux.
•	React: Biblioteca de JavaScript para construir interfaces de usuario, desarrollada por Facebook.
•	TensorFlow: Biblioteca de código abierto para aprendizaje automático, creada por el equipo de Google Brain.
•	Ruby on Rails: Framework de desarrollo web escrito en Ruby.
•	Django: Framework de desarrollo web de alto nivel en Python. Estos repositorios son ampliamente utilizados y contribuidos por desarrolladores de todo el mundo.
