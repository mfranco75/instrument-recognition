# 🎧 Reconocimiento de Instrumentos Musicales con Machine Learning

Este proyecto explora el reconocimiento automático de instrumentos musicales a partir de archivos de audio, combinando mi pasión por la música 🎶 con aprendizaje automático 🧠 usando Python y scikit-learn.

---

## 🔍 Descripción del Proyecto

Utilicé el dataset [IRMAS](https://www.upf.edu/web/mtg/irmas) (Instrument Recognition in Musical Audio Signals) para entrenar un modelo que pueda identificar qué instrumento predomina en un clip de audio de 3 segundos.

El pipeline se desarrolló en un Jupyter Notebook, e incluye:

- Extracción de características acústicas: MFCCs, ZCR, Spectral Centroid y Chroma.
- Entrenamiento con Random Forest optimizado usando GridSearchCV.
- Evaluación con métricas de clasificación y matriz de confusión.
- Pruebas con grabaciones reales.

---

## 🧰 Tecnologías utilizadas

- Python 3.12
- `librosa` para procesamiento de audio
- `scikit-learn` para entrenamiento del modelo
- `matplotlib` y `seaborn` para visualización
- Jupyter Notebook en WSL2

