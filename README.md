# Airline-Sentiment-Analysis
# ✈️ Análisis de Sentimiento de Tweets sobre Aerolíneas

Este proyecto realiza un análisis exploratorio del sentimiento de los usuarios en Twitter hacia distintas aerolíneas estadounidenses. Utiliza datos etiquetados con sentimientos (positivo, negativo o neutral), razones negativas y niveles de confianza para extraer insights y patrones de comportamiento.

---

## 📁 Dataset

El conjunto de datos fue descargado de Kaggle mediante `kagglehub`:

- 📦 [Twitter US Airline Sentiment - Kaggle](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment)
- Contiene miles de tweets etiquetados con:
  - Sentimiento (positivo, neutral, negativo)
  - Aerolínea mencionada
  - Razón de la queja (en caso de sentimiento negativo)
  - Nivel de confianza en la clasificación

---

## 🎯 Objetivos del análisis

- Conocer la distribución general de sentimientos hacia las aerolíneas.
- Identificar cuáles son las aerolíneas con mayor volumen de críticas.
- Estudiar las razones negativas más frecuentes.
- Analizar los tweets por hora del día y día de la semana.
- Examinar la coherencia entre las etiquetas de sentimiento y su nivel de confianza.
- Visualizar patrones textuales con WordClouds.

---

## 🧪 Tecnologías usadas

- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- WordCloud
- KaggleHub

---

## 📊 Visualizaciones destacadas

### 1. Distribución de Sentimientos

![Distribucion de sentimientos](https://github.com/user-attachments/assets/6415df27-2be9-4321-9138-63694a346fce)

---

### 2. Tweets por Aerolínea y Sentimiento

![Tweets por aerolínea](images/tweets_by_airline_and_sentiment.png)

---

### 3. Razones Negativas Más Comunes

![Razones negativas](images/negative_reasons_count.png)

---

### 4. WordCloud: Pérdida de equipaje y vuelo cancelado

![WordCloud Customer Service](images/wordcloud_customer_service.png)

---

### 5. Distribución Horaria de Tweets

![Tweets por hora](images/tweets_by_hour.png)

---

### 6. Distribución de Confianza en Etiquetado

![Confianza](images/confidence_distribution.png)

---

## 🗃 Estructura del repositorio

Airline-Sentiment-Analysis/
│
├── data/ # Instrucciones para obtener los datos
├── notebook/
│ └── airline_sentiment_analysis.ipynb
├── images/ # Visualizaciones exportadas
├── README.md
└── requirements.txt (opcional)


📌 Conclusiones
- La mayoría de los tweets reflejan sentimientos negativos hacia las aerolíneas.

- United y American Airlines acumulan el mayor volumen de críticas.

- Las quejas más comunes están relacionadas con el servicio al cliente, retrasos y pérdida de equipaje.

- Existen tweets mal etiquetados con baja confianza, que han sido filtrados.

- Los tweets negativos se concentran principalmente durante el día y entre semana.

- El análisis textual confirma patrones de quejas frecuentes por tipo.
