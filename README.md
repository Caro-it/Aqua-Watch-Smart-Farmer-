# Aqua-Watch: Smart-Farmer 🌱💧

Sistema inteligente de gestión de recursos hídricos para huertos escolares y comunitarios, basado en datos climáticos masivos de NOAA y Machine Learning.

## 🎯 Problema

El uso ineficiente del agua en agricultura representa uno de los mayores desperdicios de recursos naturales. Aqua-Watch predice las necesidades de riego óptimas usando datos climáticos en tiempo real, ayudando a comunidades educativas y rurales a cultivar de manera sostenible.

## 📊 Dataset

- **Fuente principal:** `bigquery-public-data.noaa_gsod` (Global Surface Summary of the Day)
- **Variables clave:** temperatura media/máxima/mínima, precipitación, punto de rocío, humedad, velocidad del viento
- **Cobertura:** estaciones meteorológicas globales desde 1929

## 🛠️ Stack Tecnológico

- **Data Science:** Python, Pandas, NumPy, Scikit-Learn
- **Cloud:** Google BigQuery
- **Visualización:** Plotly, Matplotlib
- **UI (Vibe Coding):** Streamlit
- **Notificaciones:** Sistema automatizado vía Cursor

## 📁 Estructura del Proyecto

\```
Aqua-Watch-Smart-Farmer/
├── notebooks/      # EDA y modelado en Colab
├── src/            # Código fuente del modelo
├── app/            # Aplicación Streamlit
├── data/           # Datos procesados
└── docs/           # Documentación y análisis ético
\```

## 🚀 Cómo correrlo

\```bash
pip install -r requirements.txt
streamlit run app/streamlit_app.py
\```

## 🧠 Hallazgos del EDA

_(Se completará tras el análisis exploratorio)_

## ⚖️ Consideraciones Éticas

- **Sesgo geográfico:** las estaciones NOAA tienen mayor densidad en países desarrollados
- **Validación humana:** las recomendaciones del modelo son sugerencias, no decisiones automáticas
- **Human augmentation:** el sistema asiste al agricultor, no lo reemplaza

## 👥 Equipo

-Paola Tron Escobosa, Doralcris Perez, Marcela Muñoz, Carolina kaechele  


## 📜 Licencia

MIT
