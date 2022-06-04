# NLP
Práctica entregable del módulo de "NLP" - Keepcoding

## Estructura
Dividido en 4 partes

### 1. Descarga y exploración del corpus
* Cardinalidad del vocabulario
* Distribución de reviews por número de estrellas
* Nº de reviews positivas y negativas
* N-grams más frecuentes
* Nubes de palabras
* Visualización en 2 dimensiones de algunos word embeddings calculados con Word2Vec (elegir 4-5 palabras y pintar las top 10 más similares)
* Conclusiones de la exploración
* Cualquier otra métrica / exploración / cálculo que el alumno considere

#### Tecnologías usadas
nltk, WordCloud, gensim, json, pandas, itertools...

#### Estrategias
Tokenizado, Normalizado de palabra, Stop Words, Stemming, Lemmatization, Bag of words, N-Grams, WordCloud, Sentimiento

#### Word embedding
Hyperparameters, Word2Vec, construcción del vocabulario, Skip Gram vs CBOW y visualización

### 2. Etapa de preprocesado de texto
Train-Test, Definición del Pipeline

### 3. Etapa de entrenamiento y testeo de un modelo de análisis de sentimiento
#### Modelos 
1. TF-IDF + LogisticRegression
2. Bag_of_Words + LogisticRegression
3. LSTM Word-Embedding (Word2Vec - CBOW)

### 4. Reporte de métricas y conclusiones
* Matrix de confusión
* **Métricas:** Precisision, recall, f1-score, support
* Conclusión
