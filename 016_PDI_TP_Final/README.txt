# Proyecto: Detección de Casco en Imágenes con HOG + SVM

## ¿Qué contiene este cuaderno?
Este cuaderno implementa un sistema de clasificación de imágenes que predice si una persona en moto lleva casco o no. El enfoque se basa en visión por computadora tradicional:

- Carga y etiquetado de imágenes desde Google Drive.
- Preprocesamiento de imágenes (escala de grises y redimensión).
- Extracción de características con HOG (Histogram of Oriented Gradients).
- Entrenamiento de un clasificador SVM (Support Vector Machine).
- Evaluación del modelo.
- Prueba con imágenes nuevas y visualización del resultado.

Este cuaderno es ideal para demostrar cómo técnicas clásicas pueden aplicarse a un problema real usando recursos limitados.

## Cómo usarlo
1. Abrí el archivo en [Google Colab](https://colab.research.google.com/) o en Jupyter Notebook.
2. Asegurate de tener acceso a las imágenes en tu Google Drive.
3. Ejecutá las celdas en orden.
4. Leé los comentarios para entender el proceso.
5. Podés modificar las rutas o agregar tus propias imágenes para probar el modelo.

## Autoría
- **Autor:** Sebastián Flehr  
- **Año:** 2025  
- **Materia:** Técnicas de Procesamiento de Imágenes  
- **Profesor:** Matías Barreto  
- **Carrera:** Ciencia de Datos e Inteligencia Artificial – IFTS 24

## Licencia
Este proyecto se encuentra bajo la licencia MIT.  
Libre para usar, modificar y compartir.