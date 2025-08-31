# Predicciones Financieras

Repositorio dedicado al desarrollo de modelos de **predicción de precios de activos financieros** utilizando Python, Pandas, NumPy y Scikit-learn.

---

## 🔍 Descripción

Este proyecto busca crear modelos de predicción financiera basados en datos históricos de activos (acciones, criptomonedas, commodities). Se implementan técnicas de **Machine Learning** para anticipar movimientos de precios a 1 semana, 1 mes, 3 meses y 6 meses.

---

## 🚀 Estado del Proyecto

- [x] Preparación de datasets históricos
- [ ] Optimización de modelos
- [ ] Incorporación de modelos avanzados (LSTM, Random Forest)
- [ ] Dashboard interactivo para visualización de predicciones

---

## 🛠 Tecnologías

- Python 3.x
- Pandas, NumPy, Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebooks / Google Colab

---

## 📁 Estructura del repositorio

predicciones_financieras/
├── data/ # Datasets históricos
├── notebooks/ # Notebooks de análisis y predicción
├── src/ # Scripts de Python reutilizables
├── requirements.txt # Dependencias del proyecto
└── README.md # Documentación del proyecto
---

## 💡 Cómo contribuir

1. Haz un fork del repositorio.
2. Crea tu rama: `git checkout -b feature/nueva-funcionalidad`
3. Haz commit: `git commit -m "Agrega descripción"`
4. Envía un pull request.

Revisa los [issues](https://github.com/josecarlosperalta/predicciones_financieras/issues) marcados como `good first issue` o `help wanted`.

---

## 📊 Ejemplo de uso rápido

```python
import pandas as pd
from src.modelo_prediccion import entrenar_modelo

# Cargar dataset
data = pd.read_csv('data/acciones.csv')

# Entrenar modelo
modelo = entrenar_modelo(data)

# Predecir precios futuros
predicciones = modelo.predict(data)
print(predicciones.head())

---

Autor: José Carlos Peralta


###  Contacto Profesional

-  LinkedIn: [Jose Carlos Peralta](https://www.linkedin.com/in/elcontadorperalta/)
-  GitHub: [josecarlosperalta](https://github.com/josecarlosperalta) 
-  Email: jose.estudioperalta@gmail.com
