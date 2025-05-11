# Comparativa CPU vs GPU del Filtro Sobel usando Python

Este repositorio contiene el estudio experimental y teórico del rendimiento computacional del filtro de Sobel, comparando su implementación en:

- **CPU (Python puro)**
- **GPU (PyCUDA con memoria compartida)**

El estudio incluye análisis de:
- Tiempo de ejecución
- Escalabilidad con el tamaño de imagen
- Calidad del filtrado (precision, recall, F1)
- Transferencia host-device
- Modelo de costo computacional
- Punto de equilibrio CPU-GPU

## 📂 Estructura del proyecto

- `data/input/`: imágenes de entrada en formato `.jpg` o `.png`
- `data/output/`: resultados del procesamiento
  - `images/`: imágenes de salida
  - `plots/`: gráficas generadas con `matplotlib`
  - `tables/`: resultados en `.csv` o `.xlsx`
- `src/`: scripts base en Python puro y PyCUDA
- `notebooks/`: notebooks de análisis y visualización
- `README.md`: este archivo
- `LICENSE`: licencia del código (MIT)
- `requirements.txt`: dependencias

## ⚙️ Requisitos

Instala dependencias con:

```bash
pip install -r requirements.txt
```

## 📌 Créditos

Este proyecto forma parte de una investigación académica en procesamiento digital de imágenes acelerado con GPU en Python.
