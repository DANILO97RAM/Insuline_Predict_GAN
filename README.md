# Insuline_Predict_GAN

Este proyecto tiene como objetivo entrenar un modelo generativo capaz de predecir el comportamiento de la insulina de un paciente, basado en sus primeras 16 muestras de insulina e ingesta. El código desarrollado está escrito en TensorFlow utilizando Python. Se han explorado y entrenado tres tipos diferentes de arquitecturas para el generador en el contexto de una Red Adversaria Generativa (GAN).

## Objetivo

El objetivo principal de este proyecto es desarrollar un modelo de GAN que pueda generar predicciones precisas del comportamiento de la insulina en pacientes. Esto podría tener aplicaciones significativas en el campo de la medicina y el tratamiento de la diabetes.

## Tecnologías Utilizadas

- TensorFlow: Se ha utilizado TensorFlow, una popular biblioteca de código abierto de aprendizaje automático, para construir y entrenar los modelos de GAN.
- Python: El código se ha implementado en el lenguaje de programación Python debido a su flexibilidad y amplio soporte para el aprendizaje automático.
- Otras Bibliotecas: Se han empleado diversas bibliotecas complementarias, como NumPy, pandas y matplotlib, para la manipulación de datos y la visualización.

## Estructura del Repositorio

- `architecturas/`: Esta carpeta contiene los códigos y archivos asociados a las diferentes arquitecturas de generador que se han entrenado.
- `datasets/`: Aquí se encuentran los conjuntos de datos utilizados para el entrenamiento y validación del modelo.
- `resultados/`: En esta carpeta se almacenan los resultados, gráficos y otros datos generados durante el proceso de entrenamiento.
- `utils/`: Contiene scripts y funciones auxiliares utilizados en el proyecto.
- `main.py`: Este archivo es el punto de entrada principal del proyecto y contiene el flujo principal de código para cargar, entrenar y evaluar el modelo.
- `requirements.txt`: Un archivo que enumera todas las dependencias necesarias para reproducir el entorno del proyecto.

## Instrucciones de Uso

1. Clona este repositorio en tu máquina local.
2. Instala las dependencias requeridas ejecutando el siguiente comando (se recoeminda el uso de un entorno de python):
´pip install -r requirements.txt´
3. Explora las diferentes carpetas y archivos para comprender la estructura y el funcionamiento del proyecto.
4. Ejecuta el archivo `main.py` para cargar y entrenar el modelo GAN.

## Contribuciones

Las contribuciones a este proyecto son bienvenidas. Si deseas contribuir, asegúrate de seguir las mejores prácticas de desarrollo y utiliza ramas separadas para cada nueva característica o corrección de errores.

## Licencia

Este proyecto está bajo la Licencia [MIT](LICENSE).