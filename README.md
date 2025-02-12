# Trabajo Práctico II - Aprendizaje Automático II

## Alumno
- **Fontana, Gustavo**

---

## Redes Recurrentes

Este repositorio contiene el desarrollo de dos problemáticas que abordan diferentes aplicaciones de redes recurrentes, con el objetivo de resolver cada una mediante el uso de esta arquitectura.

---

## Objetivos

Los principales objetivos de este trabajo son:

1. Utilizando datos que contiene clips de audio correspondientes a oraciones habladas en distintos idiomas, se construye un modelo de clasificación utilizando redes neuronales para inferir el idioma correspondiente.

2. Se presenta un conjunto de datos correspondientes a escritos de Shakespear con el fin de crear un modelo capaz de generar texto con dialecto de época y escritura en verso y prosa.
   - Se experimenta con los siguientes tipos de modelos:
     - Caracter a caracter: modelo de generación de texto a nivel de caracteres.
     - Palabra a palabra: modelo de generación de texto a nivel de palabras.

---

## Contenido del Repositorio

1. ### **Carpeta PROBLEMA1**
   - Contiene una notebook que desarrolla el **Ejercicio 1**, incluyendo análisis exploratorio, construcción del modelo y evaluación de métricas de desempeño.
   - Links de los datasets de referencia:
     - [Idioma Español](https://www.tensorflow.org/datasets/catalog/xtreme_s#xtreme_sfleurses_419)
     - [Idioma Francés](https://www.tensorflow.org/datasets/catalog/xtreme_s#xtreme_sfleursfr_fr)
     - [Idioma Inglés](https://www.tensorflow.org/datasets/catalog/xtreme_s#xtreme_sfleursen_us)
     - [Idioma Japonés](https://www.tensorflow.org/datasets/catalog/xtreme_s#xtreme_sfleursja_jp)

2. ### **Carpeta PROBLEMA2**
   - Esta carpeta contiene una notebook que desarrolla el **Ejercico 2** con la construcción de los modelos y el análisis cualitativo de los fragementos generados por cada uno de ellos.
   - Link al dataset utilizado:
     - [Shakespear Dataset](https://storage.googleapis.com/download.tensorflow.org/data/shakespeare.txt)
