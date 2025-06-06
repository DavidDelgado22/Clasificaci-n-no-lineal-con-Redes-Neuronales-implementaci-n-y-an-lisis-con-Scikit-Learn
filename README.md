# Clasificación con Redes Neuronales Artificiales usando `make_moons` 

Este proyecto implementa una red neuronal artificial (RNA) utilizando el conjunto de datos sintéticos `make_moons` de `scikit-learn`, con el objetivo de comprender su funcionamiento básico en una tarea de clasificación binaria no lineal. Se utiliza `MLPClassifier` para construir, entrenar y evaluar el modelo, y se incluyen visualizaciones para facilitar la interpretación de resultados.

---

## Objetivos

- Comprender la estructura básica de una red neuronal artificial (capas ocultas, funciones de activación, tasa de aprendizaje, etc.).
- Entrenar una RNA sobre un conjunto de datos no lineal.
- Evaluar el rendimiento del modelo y visualizar su frontera de decisión.
- Comparar diferentes configuraciones arquitectónicas y funciones de activación.
- Presentar conclusiones y análisis crítico.

---

## Tecnologías utilizadas

- **Python 3.11**
- **scikit-learn**
- **NumPy**
- **Matplotlib**

---

## Datos utilizados

El conjunto de datos `make_moons` consiste en 1000 muestras generadas artificialmente que forman dos medias lunas entrelazadas. Es útil para probar algoritmos de clasificación no lineal.

```python
from sklearn.datasets import make_moons

X, y = make_moons(n_samples=1000, noise=0.2, random_state=42)

