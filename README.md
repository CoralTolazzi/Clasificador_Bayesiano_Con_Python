Trabajo Práctico N.º 5 - Clasificación de Noticias con Naive Bayes
Nombre: Coral Tolazzi
Materia: TSCIA
Tema: Clasificación de Noticias
Profesora: Yanina Ximena Scudero
Cuatrimestre: 2.º Cuatrimestre del 2025
Instituto: Instituto Tecnológico Beltrán

Descripción

Este trabajo práctico consiste en la implementación de un clasificador automático de noticias utilizando el modelo de Naive Bayes Multinomial. El objetivo es detectar si una noticia es real o falsa, basándose en su contenido textual. Se emplea el procesamiento de texto con CountVectorizer y la librería scikit-learn para entrenar y evaluar el modelo.

Funcionalidades

Preprocesamiento de texto:
Conversión de documentos a vectores de frecuencia mediante CountVectorizer.

División de datos:
Separación de las noticias en conjunto de entrenamiento y prueba con train_test_split.

Entrenamiento del modelo:
Uso del clasificador Multinomial Naive Bayes.

Evaluación del modelo:

Cálculo de la precisión (accuracy).
Matriz de confusión para observar los aciertos y errores.

Clasificación de nuevas noticias:
Predicción de etiquetas para ejemplos no vistos.
