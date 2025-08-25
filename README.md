# Práctica de expresiones regulares con Python 

Este repositorio contiene el enunciado de la práctica de la segunda semana.

## Modalidad de presentación

1. Debes crear un nuevo repositorio en tu cuenta de GitHub a partir de este Template. Para ello utiliza el botón "Utilizar este template"
2. Luego en tu repositorio, debes crear los archivos necesarios para resolver el proyecto.
3. Finalmente, presentar en WebAsignatura el enlace de tu repositorio.

## Estructura

- En el directorio `data` encontrarás los archivos `.html` necesarios para resolver el enunciado. Todos los archivos tienen un mismo formato. Puedes visualizarlos en un browser.
- En el directorio `notebooks` deberás crear un archivo de Jupyter Notebook que resuelva este proyecto.

## Enunciado

La Administración de Seguridad Social tiene ordenados por año los nombres más populares para los bebés nacidos ese año en EE.UU. En el directorio `data` tienes una copia de alguno de esos archivos.

En lugar de tratar los nombres de niños y niñas por separado, los agruparemos por completo. En algunos años, un nombre aparece más de una vez en el código HTML, pero solo utilizaremos un número por nombre (el primero que aparezca).

- Utilizando expresiones regulares debes encontrar el año, extraerlo y mostrarlo.
- Extrae los nombres de niños y de niñas con el correspondiente número que ocupan en el ranking y muéstralos.
- Guarda los nombres (individuales) y su ranking en un diccionario e imprímelos,
- Crea una lista con los nombres ordenados alfabéticamente y muéstrala.
- Crea una lista con el siguiente formato y muéstrala:
  - El primer elemento debe contener un string con el "año",
  - Los siguientes elementos deben contener un string con el "nombre y la posición del ranking" ordenados en forma alfabética.
