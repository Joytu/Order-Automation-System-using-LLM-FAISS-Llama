## 🧠 [Order Automation System using LLM, FAISS, and Llama](https://github.com/yourusername/yourrepo/blob/main/Order_Automation_System.ipynb)

This notebook implements an end-to-end system for **automating the processing of customer orders** for steel products in a foreign language. It intelligently maps informal queries to structured product orders with specific catalog SKUs.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1pyveL06cXCtUuzkXJ3YOLNKxNiCL_1Cz?usp=sharing)

---

### 🔸 System Overview

- Transforms customer queries in Spanish into structured product orders  
- Maps informal descriptions to specific catalog SKUs  
- Extracts quantities, dimensions, and material specifications  

### 🔸 Technical Components

- **Universal Sentence Encoder (Multilingual)** — for 512-dimensional embeddings  
- **FAISS vector database** — uses L2 distance for efficient semantic similarity search  
- **Llama 3.3-70B Instruct Turbo** — large language model for complex reasoning  
- **Hybrid scoring** — combining semantic similarity with attribute-level matching  
