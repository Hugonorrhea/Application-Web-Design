# Ayuda Dios
***
Víctor Hugo Sánchez Martínez | 2968466 | IDS | 6to Semestre.
# Asignatura
***
Diseño de aplicaciones web | José Ricardo Zapata Solis.
# Markdown
***
Markdown es un lenguaje de marcado sencillo que sirve para agregar formato, vínculos e imágenes con facilidad al texto simple. Se puede utilizar en los siguientes lugares: Comentarios de ticket (desde la interfaz del usuario)

# Markdown etiquetado.
***
Encabezados:
Para crear encabezados, puedes utilizar el símbolo # seguido del texto del encabezado. Cuantos más # pongas, menor será el nivel del encabezado.

Texto en negrita:
Puedes aplicar formato de negrita al texto usando el doble asterisco (**) o el doble guion bajo (__)

Texto en cursiva:
Para aplicar formato de cursiva al texto, utiliza el asterisco simple (*) o el guion bajo simple (_)

Lista desordenada:
Crea listas desordenadas utilizando guiones, asteriscos o signos de suma seguidos de espacio.

Lista ordenada:
Las listas ordenadas se crean utilizando números seguidos de un punto y un espacio.

Enlaces:
Para insertar enlaces, utiliza corchetes para el texto del enlace y paréntesis para la URL.

Imágenes:
Inserta imágenes de manera similar a los enlaces, pero precede la sintaxis con un signo de exclamación.

Citas:
Utiliza el símbolo > para crear citas.

Código en línea:
Para resaltar código en línea, utiliza comillas simples (`) o comillas invertidas (```).

Bloques de código:
Coloca tu código entre tres comillas invertidas (```) y especifica el lenguaje opcionalmente.

# Markdown comandos.
***

1 Comprobar el estado de un repositorio local:
Para verificar el estado de tu repositorio local y ver qué archivos han sido modificados, añadidos o eliminados, utiliza el siguiente comando:

bash
git status

2 Añadir archivos individuales o globalmente:

Para agregar archivos específicos al área de preparación (staging area), utiliza el siguiente comando, reemplazando "nombre_del_archivo" con el nombre real del archivo:

bash
git add nombre_del_archivo

Si deseas agregar todos los archivos modificados al área de preparación, utiliza:
bash
git add .

3 Añadir comentarios a la confirmación:

Después de haber añadido los archivos al área de preparación, realiza una confirmación (commit) con un comentario descriptivo utilizando el siguiente comando:
bash
git commit -m "Tu mensaje descriptivo aquí"

4 Subir los cambios al repositorio remoto:

Para enviar tus cambios al repositorio remoto (por ejemplo, en GitHub), utiliza el siguiente comando, reemplazando "nombre_rama" con el nombre de la rama en la que estás trabajando:
bash
git push nombre_remoto nombre_rama

Por lo general, el nombre remoto es "origin" y la rama principal se llama "main" o "master".

5 Crear, navegar y borrar ramas:

Crear una nueva rama:
bash
git branch nombre_nueva_rama

6. Cambiar a una rama existente:

bash
git checkout nombre_rama

O, de manera más reciente:
bash
git switch nombre_rama

Borrar una rama (después de haber fusionado los cambios):
bash
git branch -d nombre_rama

Si la rama no ha sido fusionada y deseas forzar la eliminación, usa:
bash
git branch -D nombre_rama
