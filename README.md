# RedNeuronalAloeVera
Este repositorio muestra el codigo hecho en google colabs para llevar a cabo una red neuronal convolucional para la clasificación de imágenes de Aloe Vera.

## Requisitos previos

- Python 3.8 o superior
- Dependencias: `tensorflow`, `kagglehub`

## Ejecución en Google Colab (recomendado)

1. Haz clic en el siguiente enlace para abrir el notebook directamente en Google Colab:

   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Amonwill/RedNeuronalAloeVera/blob/main/AloeveraRN.ipynb)

2. Una vez abierto en Colab, ve al menú **Entorno de ejecución > Ejecutar todas** (o presiona `Ctrl+F9`) para ejecutar todas las celdas.
3. El notebook descargará automáticamente el dataset desde Kaggle, entrenará el modelo y generará el archivo `modelo_aloe.tflite`.
4. Al finalizar, el archivo `.tflite` se descargará automáticamente a tu equipo.

## Ejecución local

1. Clona el repositorio:

   ```bash
   git clone https://github.com/Amonwill/RedNeuronalAloeVera.git
   cd RedNeuronalAloeVera
   ```

2. Instala las dependencias necesarias:

   ```bash
   pip install tensorflow kagglehub
   ```

3. Abre y ejecuta el notebook con Jupyter:

   ```bash
   pip install jupyter
   jupyter notebook AloeveraRN.ipynb
   ```

4. Ejecuta todas las celdas del notebook en orden. El modelo entrenado se guardará como `aloe_modelo.h5` y `modelo_aloe.tflite` en el directorio actual.

> **Nota:** Para la descarga del dataset mediante `kagglehub`, es posible que necesites configurar tus credenciales de Kaggle. Consulta la [documentación de kagglehub](https://github.com/Kaggle/kagglehub) para más detalles.
