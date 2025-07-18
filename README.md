
# 🧠 TFM: Detección de Fake News y Análisis de Temas

Este repositorio contiene el código desarrollado para el Trabajo de Fin de Máster (TFM), centrado en la detección de noticias falsas, el análisis de sentimientos y el modelado de temas mediante técnicas de aprendizaje automático y modelos de lenguaje como BERT.

---

## 📌 Objetivos del proyecto

- Detectar noticias falsas utilizando modelos clásicos de clasificación y modelos preentrenados (BERT).
- Analizar el sentimiento de textos noticiosos y evaluar su relación con la veracidad.
- Modelar los temas presentes en los textos utilizando BERTopic y LDA.
- Comparar el rendimiento de diferentes enfoques y estudiar la coherencia y diversidad de los temas.

---

## 🗂 Estructura del repositorio

```
📁 datasets/                     # Datos procesados y ejemplos (pueden ser .csv)
📁 models/                       # Notebooks explicativos y experimentales
📁 notebooks/
    ├── ML_fake_news_opt                  # Limpieza y tokenización de textos
    ├── ML_fake_news.py                   # Entrenamiento y evaluación de modelo BERT
    ├── Bert_fake_news.py                 # Entrenamiento de SVM, Random Forest, etc.
    ├── Bert_sentiment_analysis.py        # BERTopic y LDA
    ├── Topic_Modeling_LDA.py             # BERTopic y LDA
    ├── ML_sentiment_analysis_opt.py      # BERTopic y LDA
    ├── Topic_Modeling_Bertopic_opt.py    # BERTopic y LDA
    ├── Topic_Modeling_Bertopic.py        # BERTopic y LDA
    ├── final.py                          # BERTopic y LDA
    └── ML_sentiment_analysis.py          # Funciones auxiliares
README.md
requirements.txt
```

---

## ⚙️ Requisitos

```bash
python >= 3.8
```

### Instalar dependencias

```bash
pip install -r requirements.txt
```

### Principales librerías usadas:

- `scikit-learn`
- `pandas`, `numpy`
- `transformers`
- `BERTopic`
- `gensim`
- `matplotlib`, `seaborn`
- `optuna` (para optimización de hiperparámetros)

---

## 📊 Evaluación

- Accuracy, F1-score, Precision, Recall
- Matriz de Confusión
- Coherence score para evaluar temas

---

## 📎 Datos

Este proyecto utiliza un conjunto de datos de noticias etiquetadas como verdaderas o falsas, obtenido de fuentes públicas.

> ⚠️ Los archivos de datos no se incluyen por tamaño o privacidad. Puedes adaptar el código para cualquier dataset similar.

---

## 🔗 Enlaces relevantes

- [TFM completo en PDF](https://link-a-tu-tfm.com)
- [Dataset original (si es público)](https://kaggle.com/...)

---

## 📄 Licencia

Este proyecto se distribuye bajo la licencia MIT. Ver el archivo `LICENSE` para más detalles.

---

## 👨‍💻 Autor

Juan Pablo Batista Hernández  
Trabajo de Fin de Máster — [Nombre del máster y universidad]  
Año: 2025
