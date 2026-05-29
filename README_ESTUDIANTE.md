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


git practica 2
Taller GIT. Práctica 2. Guarda los comandos realizados, así como los resultados(capturas), integrarlo dentro del mismo repositorio

Trabajar con un proyecto HTML y un repositorio local.
Crea una carpeta practica-taller-git en tu pc.
Inicializa el repositorio.
git init
Crea el fichero index.html con un html simple.
Comprueba que el repositorio a detectado el cambio.
git status
Añade el fichero al stage.
git add index.html.
Confirma los cambios.
git commit -m “added index file”
Añade un fichero description.html y edita index.html.
Comprueba que ha detectado el nuevo fichero y la modificación de index.
git status
git diff
Crea un fichero TODO.txt de tareas pendientes.
Comprueba que git ha detectado el nuevo fichero.
git status
Ignora el fichero TODO.txt ya que es donde anotaremos nuestras tareas personales y no debe formar parte del proyecto. Para ello crea un fichero .gitignore con la linea TODO.txt.
Comprueba que ya no detecta el nuevo fichero TODO.txt (si que detectara el .gitignore claro).
git status
Añade y confirma el .gitignore.
Puedes continuar añadiendo ficheros html, css e imágenes para probar el repositorio.
Haz un fork del repositorio creado para la práctica del taller:
Entra en https://github.com/
Accede a tu cuenta.
Accede al repositorio del profesor https://github.com/lalobarri/git-practica-2.git
Pulsa el botón fork (parte superior derecha) para crearte una copia del mismo en tu cuenta.
Clona el repositorio en tu equipo en otra carpeta diferente que la llamaremos 'git-practica-2'. Quedará algo parecido a lo siguiente:
git clone https://github.com/[tu-nombre-de-usuario]/git-practica-2.git
Crea un nuevo fichero en el proyecto que se llame [tu-nombre-de-usuario].html
Edita el fichero añadiendo como título tu nombre, algún texto y lo que desees en el.
Añade el fichero al repositorio.
Súbelo al repositorio remoto (github).
git push
Crea una rama develop y cámbiate a ella.
git checkout -b develop
Realiza cambios en el proyecto, confírmalos y súbelos al repositorio remoto.
git status
git add *
git commit -m "Mensaje del commit..."
git push origin
Desde github crea un pull request de la rama develop a main.
Fusiona la rama develop con en main. No deberías de tener ningún conflicto.
Haz nuevos cambios en el proyecto siguiendo el flujo de trabajo git flow.
Preguntas
Crea un nuevo fichero respuestas.md, contesta las siguientes preguntas y súbelo a tu repositorio remoto de github:

¿Qué sucede cuando hacemos un git add?
¿Qué sucede cuando hacemos un git commit? ¿Dónde está ese commit?
¿Por qué al hacer git commit todavía no está disponible ese commit en el repositorio remoto?
¿Qué hay que hacer para que veamos este commit en nuestro repositorio remoto de github?
¿Qué diferencia hay entre hacer un fork o crear una nueva rama?
¿Qué comando se utiliza para crear una nueva rama sin cambiarte a ella?
¿Cuál es la diferencia entre los comandos git switch y git checkout al trabajar con ramas?
¿Qué es una rama por defecto (como main o master) y por qué es importante?
¿Qué comando te permite ver la lista de todas las ramas locales de tu repositorio?
En el contexto de Git, explica con tus propias palabras qué es una rama (branch) y cuál es su beneficio principal al trabajar en un proyecto de software
¿Qué ha pasado con el contenido de la carpeta practica-taller-git? ¿Por qué no la podemos ver en nuestro repositorio remoto de github?
