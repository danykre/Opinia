# 📊 Proyecto Final – Data Science: NLP & Deep Learning  
📌 **Descripción**  
Este proyecto desarrolla un sistema completo de **análisis de sentimiento** para la empresa *Opinia*, que recibe miles de reseñas mensuales de sus clientes.  
Se implementó un flujo integral de Data Science aplicado al texto: limpieza, tokenización, lematización, vectorización, análisis exploratorio, modelado predictivo y comparación entre enfoques de Machine Learning y Deep Learning.

El trabajo fue realizado en el marco del proyecto *Data Science: NLP & Deep Learning*, aplicando técnicas modernas de procesamiento del lenguaje natural.

---

## 📂 Archivos del repositorio  
- **opinia_reviews_v2.csv** → Dataset sintético utilizado para el análisis.  
- **proyecto_final.ipynb** → Notebook con el proceso completo: NLP, EDA, modelado y comparativa de modelos.  
- **Presentacion.pdf** → Resumen ejecutivo del proyecto, orientado a stakeholders no técnicos.  

---

## 🔍 Metodología  

### **NLP – Procesamiento del Lenguaje Natural**  
- Limpieza de texto (normalización, eliminación de signos, tildes y números)  
- Tokenización  
- Eliminación de stopwords  
- Lematización  
- Vectorización TF-IDF y secuencias tokenizadas  

### **EDA (Exploratory Data Analysis)**  
- Distribución de ratings  
- Extensión del texto vs. puntuación  
- WordCloud global, positiva y negativa  
- Frecuencias de palabras y análisis de n-gramas  

### **Modelado**

#### **Machine Learning**  
- Regresión Logística  
- Representación TF-IDF (uni-gramas y bi-gramas)  
- Métrica principal: Accuracy  

#### **Deep Learning**  
- Arquitectura **MLP (Multilayer Perceptron)**  
- Tokenizer + Text to Sequence (Keras)  
- Capas densas + Dropout  
- Métrica principal: Accuracy  

### **Comparación y evaluación**  
- División del dataset: 80% entrenamiento / 20% prueba  
- Matrices de confusión  
- Análisis de errores entre ratings vecinos  

---

## 📊 Resultados principales  
- Ambos modelos lograron un **accuracy cercano al 93%**  
- El modelo de Machine Learning se destacó por su interpretabilidad  
- La red neuronal mostró mayor estabilidad en validación  
- Las reseñas negativas tienden a ser más largas y detalladas  
- El vocabulario de opiniones positivas y negativas mostró patrones claros (n-gramas consistentes)

👉 El proyecto demuestra que tanto enfoques clásicos como redes neuronales pueden resolver con eficacia tareas de análisis de sentimiento si cuentan con un pipeline sólido de preprocesamiento.

---

## 🚀 Líneas futuras  
- Incorporar embeddings como Word2Vec, GloVe o modelos tipo **BETO/BERT para español**  
- Procesamiento en tiempo real para nuevas reseñas  
- Extender el análisis a otros idiomas o canales (RRSS, encuestas, soporte)  
- Construcción de dashboard para monitoreo de sentimiento  

---

## 🛠️ Tecnologías utilizadas  
- **Python** → Pandas, NumPy, Matplotlib, Scikit-learn, Keras/TensorFlow, NLTK/spaCy  
- Excel  
- Jupyter Notebook  
- GitHub  
- ChatGPT  
- Canva  

---

## 👨💻 Autor  
**Daniel Kresisch** 
