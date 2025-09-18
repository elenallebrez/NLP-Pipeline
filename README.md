# NLP-Pipeline
Data processing and NLP pipelines for chatbot conversations.

This repository contains scripts and notebooks for:
- **Generating embeddings** with OpenAI and Gemini models.
- **Comparing embeddings** across providers.
- **Context extraction** of chatbot conversations.
- **Synthetic dataset generation** for moderation and cultural adaptation tasks.

---

## 📂 Project Structure
````
┣ 📁 Context
┃ ┣ Context.ipynb
┣ 📁 Data Cleaning 1
┃ ┣ DataCleaning1.ipynb 
┣ 📁 Data Cleaning 2
┃ ┣ DataCleaning2.ipynb
┣ 📁 DataRedFlagGeneration
┃ ┣ DataCleaning2.ipynb
┣ 📁 Embeddings
┃ ┣ 📁 embeddingopenAIFiles/ # Embeddings generated with OpenAI
┃ ┣ 📁 embeddingGeminiFiles/ # Embeddings generated with Gemini
┃ ┣ DataCleaning2.ipynb
┃ ┣ DataCleaning2.ipynb
┃ ┣ DataCleaning2.ipynb
┗ README.md
````

---

## 🚀 Main Scripts

### 🔹 Embedding Generation
- `EmbeddingOpenAI.ipynb` → Generates embeddings using **OpenAI**.
- `EmbeddingGemini.ipynb` → Generates embeddings using **Gemini**.

### 🔹 Embedding Comparison
- `ComparisionEmbeddings.ipynb` → Loads embeddings from both models and computes **cosine similarity** to measure alignment.

### 🔹 Context
- `Context.ipynb` → Extracts **cultural context summaries** from conversations.

### 🔹 Data Generation
- `RedFlagDataGeneration.ipynb` → Creates synthetic datasets of **red flag sentences** for moderation.
- Output saved in CSV format with labels (`ALLOW` or `BLOCK`).

### 🔹 Data Cleaning
- `DatCleaning1.ipynb`
- `DatCleaning2.ipynb`

---

