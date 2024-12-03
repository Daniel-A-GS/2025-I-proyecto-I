# FORMATO DE PROPUESTA DE PROYECTO

## Clasificación de imágenes con redes neuronales
**Semestre:** 2025-1  
**Fecha de entrega:** 16/10/2024  

## Nombre de los Integrantes
- **Integrante 1:** García Sánchez Daniel Alfredo  
- **Integrante 2:** Guerrero López Jesús Antonio  

## 1. Título del Proyecto
**Clasificación de Diagnósticos Radiológicos de Tórax**

## 2. Objetivo
Las radiografías son uno de los estudios más comunes realizados a pacientes debido a su facilidad y bajo costo. El dataset de CXR-8 contiene más de 120,000 imágenes de radiografías de tórax de más de 30,800 pacientes únicos, obtenidas del *National Institutes of Health Clinical Center*.

**Objetivos específicos:**
1. Crear un pipeline de datos derivado en la base de datos obtenida de: [ChestX-ray8](https://paperswithcode.com/dataset/chestx-ray8).
2. Crear un clasificador multi-etiqueta utilizando redes neuronales convolucionales.
3. Desarrollar una API que permita consumir el modelo entrenado en el paso anterior para el apoyo en diagnósticos.

## 3. Herramientas para la implementación del proyecto
Este proyecto será desarrollado en **Python**, utilizando las siguientes librerías y herramientas:
- Pandas
- NumPy
- Matplotlib
- OpenCV
- Scikit-learn
- TensorFlow
- Keras

## 4. Orígenes de datos
Los datos fueron obtenidos de la página [ChestX-ray14](https://paperswithcode.com/dataset/chestx-ray14), quienes los recopilaron del *National Institutes of Health Clinical Center*.

## 5. Principales actividades a realizar
1. Partición de cada conjunto de datos (Entrenamiento, Validación, Prueba).
2. Análisis y visualización de cada conjunto de datos.
3. Procesamiento de imágenes (incluyendo posibles técnicas como Downsampling).
4. Implementación y entrenamiento del modelo con las librerías descritas, optimizando parámetros mediante análisis de performance.
5. Ajuste del modelo final con la mayor cantidad de datos posible, asegurando precisión sin sobreajuste.
6. Desarrollo de la API para implementar el modelo entrenado.

## 6. Observaciones y comentarios generales del alumno
- El costo de preprocesar 120,000 imágenes y entrenar el modelo es elevado para una sola PC. Los autores del paper original utilizaron múltiples GPUs proporcionadas por Nvidia. En caso de no encontrar forma de correr tantas imágenes reduciremos la muestra o la cantidad de enfermedades a diagnosticar.

## 7. Observaciones y resultado de la revisión del profesor