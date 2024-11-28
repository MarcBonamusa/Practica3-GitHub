# Práctica 3 - GitHub y repositorio remoto
## Parte 1: Preparación del Proyecto
### 1. Crear directorios y archivos:

- He creado el directorio GitBonamusaMarc2425, despues creamos la carpeta src dentro y el README.md

![ex1](./img/ex1.png)

### 2. Inicializa Git:

- Convertimos el respositiorio Git con git init, despues creamos .gitignore y creamos index.html, style.css, main.js en src/

![ex2.1](./img/ex2_1.png)

![ex2.2](./img/ex2_2.png)

![ex2.3](./img/ex2_3.png)

- **Que es el archivo .gitignore?** El archivo .gitignore, es un archivo de texto que le dice a Git qué archivos o carpetas ignorar en un proyecto.

- **Para que sirve el archivo .gitignore?** El archivo gitignore sirve para ignorar archivos o carpetas enteras de nuestro sistema.

![ex2.3](./img/ex2_4.png)

![ex3](./img/ex3.png)

## Parte 2: Colaboración en Equipo
### 1. Configura del repositorio remoto:

- **¿Qué pasa si creo un repositorio con el archivo README.md desde GitHub?** El repositorio remoto no estará vacío porque se crea el archivo README.md automaticamente.

- **¿Qué pasa si crea un repositorio sin el archivo README.md desde GitHub?** El repositorio remoto estará vacío y no tendrá commits iniciales ni archivos.

- **Explica las diferencias entre las 2 preguntas anteriores:**

- **Indica que comandos te da GitHub al crear un repositorio:**

1. echo "# Practica3-GitHub" >> README.md
2. git init
3. git add README.md
4. git commit -m "first commit"
5. git branch -M main
6. git remote add origin https://github.com/MarcBonamusa/Practica3-GitHub.git
7. git push -u origin main

### 2. Actualización del Proyecto:

- He creado la rama feature/documentacion, he creado un archivo docs.md y un commit

![p2ex2.1](./img/p2ex2_1.png)

![p2ex2.2](./img/p2ex2_2.png)

![p2ex2.3](./img/p2ex2_3.png)

- He usado git diff para comparar las diferencias entre main y feature/documentacion.

![p2ex3](./img/p2ex3.png)

### 3. Sincronización:

![p2ex4](./img/p2ex4.png)

## Parte 3: Gestión de Archivos y Cambios
###1. Ediciones rápidas:

- He creado el archivo src/app.py, despues lo he añadido y he hecho un commit y verificamos su estado. Con git lg vemos el historial de commits, 

![p3ex1](./img/p3ex1_1.png)

![p3ex1.2](./img/p3ex1_2.png)

![p3ex1.2.2](./img/p3ex1_2_2.png)

![p3ex1.3](./img/p3ex1_3.png)

###2. Borrado y recuperación:

###3. Combina ramas:

