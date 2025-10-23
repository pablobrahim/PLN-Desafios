**Alumno**: Pablo Brahim  
**Materia**: Procesamiento de Lenguaje Natural  
**Carrera**: Especialización en Inteligencia Artificial - FIUBA  

## Contenido
- [Introducción](#introduccion)
- [Desafío 1 - Consigna](#desafio-1---consigna)
- [Desafío 2 - Consigna](#desafio-2---consigna)
- [Desafío 3 - Consigna](#desafio-3---consigna)
- [Desafío 4 - Consigna](#desafio-4---consigna)

---

## Introduccion

Desafíos de la materia Procesamiento de Lenguaje Natural en el cuarto bimestre del año 2025.

---

## Desafío 1 - Consigna

1. Vectorizar documentos. Tomar 5 documentos al azar y medir similaridad con el resto de los documentos. Estudiar los 5 documentos más similares de cada uno analizar si tiene sentido la similaridad según el contenido del texto y la etiqueta de clasificación.  
2. Construir un modelo de clasificación por prototipos (tipo zero-shot). Clasificar los documentos de un conjunto de test comparando cada uno con todos los de entrenamiento y asignar la clase al label del documento del conjunto de entrenamiento con mayor similaridad.  
3. Entrenar modelos de clasificación Naïve Bayes para maximizar el desempeño de clasificación (f1-score macro) en el conjunto de datos de test. Considerar cambiar parámetros de instanciación del vectorizador y los modelos y probar modelos de Naïve Bayes Multinomial y ComplementNB.  
4. Transponer la matriz documento-término. De esa manera se obtiene una matriz término-documento que puede ser interpretada como una colección de vectorización de palabras. Estudiar ahora similaridad entre palabras tomando 5 palabras y estudiando sus 5 más similares. La elección de palabras no debe ser al azar para evitar la aparición de términos poco interpretables, elegirlas "manualmente".

📓 [Notebook Desafío 1](Desafio_1/Desafio_1.ipynb)

---

## Desafío 2 - Consigna

1. Crear sus propios vectores con Gensim basado en lo visto en clase con otro dataset.  
2. Probar términos de interés y explicar similitudes en el espacio de embeddings (sacar conclusiones entre palabras similitudes y diferencias).  
3. Graficarlos.  
4. Obtener conclusiones.  

📓 [Notebook Desafío 2](Desafio_2/Desafio_2.ipynb)

---

## Desafío 3 - Consigna

1. Seleccionar un corpus de texto sobre el cual entrenar el modelo de lenguaje.  
2. Realizar el pre-procesamiento adecuado para tokenizar el corpus, estructurar el dataset y separar entre datos de entrenamiento y validación.  
3. Proponer arquitecturas de redes neuronales basadas en unidades recurrentes para implementar un modelo de lenguaje.  
4. Con el o los modelos que consideren adecuados, generar nuevas secuencias a partir de secuencias de contexto con las estrategias de greedy search y beam search determinístico y estocástico. En este último caso observar el efecto de la temperatura en la generación de secuencias.  

📘 [Colab Desafío 3](https://colab.research.google.com/drive/1Rw_dGf4CJLj7RVcHxTKO7dzv_NaaGr9p#scrollTo=Iv5PEwGzZA9-)

---

## Desafío 4 - Consigna

Replicar el modelo en PyTorch.  
- Extender el entrenamiento a más datos y tamaños de secuencias mayores.  
- Explorar el impacto de la cantidad de neuronas en las capas recurrentes.  
- Mostrar 5 ejemplos de traducciones generadas.  
Replicar y extender el traductor:  

📘 [Colab Desafío 4](Desafio_4/Desafio_4.ipynb)
