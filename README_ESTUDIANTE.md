# Portafolio Profesional
## Nombre del estudiante
Omar Salinas
## Objetivo de la práctica
Personalizar una plantilla web profesional utilizando Git y GitHub.
## Tecnologías utilizadas
- HTML5
- CSS3
- JavaScript
- Git
- GitHub
## Cambios realizados
- Actualización de datos personales
- Cambio de colores (color principal cambiado a tonos azules)
- Adaptación responsiva
- Nuevas imágenes
- Sección de habilidades
## Comandos Git utilizados
- git clone
- git status
- git add .
- git commit
- git push
- git pull
- git branch
- <img width="1614" height="1032" alt="image" src="https://github.com/user-attachments/assets/28325bb5-1846-45af-bd09-c9adcbf9e55a" />

## Evidencias
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/8034a340-aefe-4b42-be32-b6a7fd51f2c9" />


## git practica 2
Taller GIT. Práctica 2. Guarda los comandos realizados, así como los resultados(capturas), integrarlo dentro del mismo repositorio

## Trabajar con un proyecto HTML y un repositorio local.
Crea una carpeta practica-taller-git en tu pc.
Inicializa el repositorio.
git init
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/d6cbc97e-8a91-4b7c-b967-285ca959c2d5" />

## Crea el fichero index.html con un html simple.
Comprueba que el repositorio a detectado el cambio.
git status
<img width="1916" height="1074" alt="image" src="https://github.com/user-attachments/assets/f84b91bc-5a4e-42c3-80dc-242c583e97f1" />

## Añade el fichero al stage.
git add index.html.
## Confirma los cambios.
git commit -m “added index file”
<img width="1912" height="1073" alt="image" src="https://github.com/user-attachments/assets/e3d15a50-00a6-44fe-b4d0-311c6e135335" />

## Añade un fichero description.html y edita index.html.
Comprueba que ha detectado el nuevo fichero y la modificación de index.
git status
git diff
<img width="1918" height="1079" alt="image" src="https://github.com/user-attachments/assets/f1a8a634-e936-45b2-83d3-105c7e16c87e" />

## Crea un fichero TODO.txt de tareas pendientes.
Comprueba que git ha detectado el nuevo fichero.
git status
<img width="670" height="396" alt="image" src="https://github.com/user-attachments/assets/e7daede3-9943-4b8a-96f7-32156150a647" />

## Ignora el fichero TODO.txt ya que es donde anotaremos nuestras tareas personales y no debe formar parte del proyecto. Para ello crea un fichero .gitignore con la linea TODO.txt.
Comprueba que ya no detecta el nuevo fichero TODO.txt (si que detectara el .gitignore claro).
git status
<img width="1587" height="1078" alt="image" src="https://github.com/user-attachments/assets/021a508c-2a1b-43c9-8e7f-820735551827" />

## Añade y confirma el .gitignore.
Puedes continuar añadiendo ficheros html, css e imágenes para probar el repositorio.
## Haz un fork del repositorio creado para la práctica del taller:
Entra en https://github.com/
Accede a tu cuenta.
Accede al repositorio del profesor https://github.com/lalobarri/git-practica-2.git
## Pulsa el botón fork (parte superior derecha) para crearte una copia del mismo en tu cuenta.
## Clona el repositorio en tu equipo en otra carpeta diferente que la llamaremos 'git-practica-2'. Quedará algo parecido a lo siguiente:
git clone https://github.com/[tu-nombre-de-usuario]/git-practica-2.git
## Crea un nuevo fichero en el proyecto que se llame [tu-nombre-de-usuario].html
<img width="1914" height="1079" alt="image" src="https://github.com/user-attachments/assets/4b9a5df8-1030-4338-b10c-cb080bd4978a" />

## Edita el fichero añadiendo como título tu nombre, algún texto y lo que desees en el.
Añade el fichero al repositorio.

## Súbelo al repositorio remoto (github).
git push
<img width="1903" height="1078" alt="image" src="https://github.com/user-attachments/assets/0bdccbb6-5a3e-4940-9b53-c3977d2d31fa" />

## Crea una rama develop y cámbiate a ella.
git checkout -b develop
## Realiza cambios en el proyecto, confírmalos y súbelos al repositorio remoto.
git status
git add *
git commit -m "Mensaje del commit..."
git push origin
<img width="1919" height="1078" alt="image" src="https://github.com/user-attachments/assets/6f519999-74d7-4642-91f0-439fd187394a" />

## Desde github crea un pull request de la rama develop a main.
Fusiona la rama develop con en main. No deberías de tener ningún conflicto.
Haz nuevos cambios en el proyecto siguiendo el flujo de trabajo git flow.
<img width="1878" height="1022" alt="image" src="https://github.com/user-attachments/assets/cd05e3b7-b7ed-43c7-94af-eb0d74036ab5" />

<img width="1896" height="881" alt="image" src="https://github.com/user-attachments/assets/581b2d84-ef9f-48c5-8730-1c83de3c4692" />

## Preguntas
## ¿Qué sucede cuando hacemos un git add?
Prepara los archivos modificados (staging area) para guardarlos en el siguiente commit.

## ¿Qué sucede cuando hacemos un git commit? ¿Dónde está ese commit?
Guarda una versión permanente de tus cambios. Este commit se guarda localmente en la carpeta oculta .git de tu computadora.

## ¿Por qué al hacer git commit todavía no está disponible ese commit en el repositorio remoto?
Porque Git trabaja de forma local; los cambios no suben a internet automáticamente.

## ¿Qué hay que hacer para que veamos este commit en nuestro repositorio remoto de github?
Debemos ejecutar el comando git push.

# ¿Qué diferencia hay entre hacer un fork o crear una nueva rama?
Una rama es una línea de trabajo paralela dentro del mismo proyecto. Un fork es una copia completa y separada del proyecto en tu propia cuenta de GitHub.

## ¿Qué comando se utiliza para crear una nueva rama sin cambiarte a ella?
git branch [nombre-de-la-rama]

## ¿Cuál es la diferencia entre los comandos git switch y git checkout al trabajar con ramas?
git checkout es un comando antiguo que sirve para muchas cosas (cambiar ramas y restaurar archivos). git switch es más moderno y sirve exclusivamente para cambiar de ramas, evitando confusiones.

## ¿Qué es una rama por defecto (como main o master) y por qué es importante?
Es la rama principal del repositorio. Es importante porque ahí debe estar siempre la versión estable y funcional del código.

## ¿Qué comando te permite ver la lista de todas las ramas locales de tu repositorio?
git branch

## En el contexto de Git, explica con tus propias palabras qué es una rama (branch) y cuál es su beneficio principal al trabajar en un proyecto de software
Es un espacio de trabajo aislado. Su beneficio es que te permite crear funciones o arreglar errores sin riesgo de dañar el código principal que ya funciona.

## ¿Qué ha pasado con el contenido de la carpeta practica-taller-git? ¿Por qué no la podemos ver en nuestro repositorio remoto de github?
Ese proyecto vive solo en tu computadora. No se ve en GitHub porque nunca lo vinculamos a un repositorio en la nube ni ejecutamos un git push.
