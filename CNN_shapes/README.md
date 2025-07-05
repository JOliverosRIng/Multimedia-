# Clasificación de Imágenes con PyTorch

Este proyecto implementa un **modelo de clasificación de imágenes** utilizando redes neuronales convolucionales (CNN) en PyTorch. El objetivo es entrenar un modelo desde cero para que sea capaz de reconocer diferentes clases de imágenes a partir de un conjunto de datos estructurado en carpetas por clase.

El código está desarrollado en un Jupyter Notebook e incluye todo el flujo completo:

- Instalación de dependencias.
- Descarga del dataset desde KaggleHub.
- Preprocesamiento y carga de datos con `ImageFolder`.
- Construcción de un modelo CNN personalizado.
- Entrenamiento del modelo con soporte para GPU (CUDA).
- Visualización de métricas como la pérdida y la precisión.
- Evaluación y muestra de predicciones sobre imágenes reales.

Este proyecto puede ser usado como parte del proceso de aprendizaje en la clase de Multimedia de la Universidad Distrital.

## 🧰 Tecnologías utilizadas

- Python 3
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- KaggleHub

## 📁 Estructura del proyecto

- `Model.ipynb`: Notebook principal donde se entrena y evalúa el modelo de clasificación.
- Se utiliza `ImageFolder` para cargar los datos de entrenamiento y prueba.

## 🚀 Cómo usar

1. Asegúrate de tener instalado Jupyter Notebook.
2. Ejecuta todas las celdas del notebook `Model.ipynb`.

## 📸 Ejemplo de salida

El modelo genera gráficos de precisión y pérdida durante el entrenamiento, y muestra imágenes clasificadas con sus respectivas etiquetas.

## 💡 Notas

- El código detecta si hay GPU disponible (CUDA) para acelerar el entrenamiento.
- El dataset debe estar organizado en carpetas por clase para ser usado con `ImageFolder`.

## ✍️ Autora

- Janeth Oliveros Ramírez  
  [GitHub](https://github.com/JOliverosRIng)
)

