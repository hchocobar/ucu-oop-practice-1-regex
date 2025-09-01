# Práctica de expresiones regulares con Python 

Este repositorio contiene el enunciado de la práctica de RegEx

## Modalidad de presentación

1. Debes crear un nuevo repositorio en tu cuenta de GitHub a partir de este Template. Para ello utiliza el botón "Utilizar este template"
2. Luego en tu repositorio, debes crear y/o modificar los archivos necesarios para resolver el proyecto.
3. Finalmente, presentar en WebAsignatura el enlace de tu repositorio.

## Estructura

- En el directorio `data` encontrarás los archivos `.html` necesarios para resolver el enunciado. Todos los archivos tienen un mismo formato. Puedes visualizarlos en un browser (Chrome, Firefox, Safari).
- En el directorio `notebooks` deberás modificar el archivo de Jupyter Notebook `notebooks/project.ipynb` para que  resuelva este proyecto.

## Criterios de Evaluación

* **PEP 8:** El código debe seguir las pautas de estilo de **PEP 8**.
* **Markdown:** El notebook `project.ipynb` debe estar bien documentado usando **Markdown** para explicar cada paso y los resultados obtenidos.
* **Funcionalidad:** Todas las tareas deben estar resueltas correctamente.

## Enunciado

### Introducción

¡Bienvenido/a a la práctica de Expresiones Regulares\! 🚀 La Administración de Seguridad Social de EE. UU. publica anualmente los nombres de bebé más populares. Los archivos en el directorio `data` contienen una muestra de estos datos en formato HTML.

El objetivo es analizar estos archivos. Simplificaremos la tarea **tratando los nombres de niños y niñas en conjunto**. Es importante notar que si un nombre aparece más de una vez en un archivo, solo debemos considerar su **primera aparición y su ranking asociado**.

### Tareas

-----

#### Tarea 1: Encontrar el Año

Utiliza una expresión regular para **extraer el año** de la primera línea de un archivo HTML. Tu código debe ser capaz de encontrar y mostrar el año como un string.

**Salida esperada:**
`Año: 2010`

-----

#### Tarea 2: Extraer Nombres y Ranking

Tu objetivo es usar una expresión regular para **extraer los nombres y su ranking**. Fíjate en la estructura del HTML para identificar el patrón que contiene el ranking y el nombre. La salida debe ser una lista de tuplas, donde cada tupla contenga el nombre y su posición.

**Ejemplo de Salida:**
`[('Isabella', '1'), ('Sophia', '2'), ('Emma', '3'), ...]`

-----

#### Tarea 3: Guardar en un Diccionario

Con los datos de la tarea anterior, crea un **diccionario** donde cada **clave sea un nombre** y su **valor sea el número de ranking**.

**Ejemplo de Salida:**
`{'Isabella': '1', 'Sophia': '2', 'Emma': '3', 'Mason': '1', 'Jacob': '2', ...}`
*Nota: Al agrupar nombres de niños y niñas, los rankings de ambos se incluirán en el mismo diccionario.*

-----

#### Tarea 4: Lista de Nombres Ordenada

A partir de tu diccionario de la tarea 3 o de la lista de la tarea 2, genera una nueva **lista que contenga solo los nombres, ordenados alfabéticamente**.

**Ejemplo de Salida:**
`['Aaliyah', 'Aaron', 'Abigail', 'Addison', ...]`

-----

#### Tarea 5: Formatear la Salida Final

Combina los resultados de las tareas 1 y 4 para crear una **lista final con un formato específico**. Esta lista debe cumplir dos reglas:

1.  El **primer elemento** es un string con el **año** extraído.
2.  Los **elementos siguientes** son strings con el formato `"nombre - ranking"`, y deben estar **ordenados alfabéticamente por el nombre**.

**Ejemplo de Salida:**
`['2010', 'Aaliyah - 100', 'Aaron - 49', 'Abigail - 8', 'Addison - 27', ...]`

-----
