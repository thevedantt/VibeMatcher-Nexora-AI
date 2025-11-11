# 🧠 **Vibe Matcher — AI-Powered Fashion Recommendation System**

---

![VibeMatcher Banner](https://github.com/thevedantt/VibeMatcher-Nexora-AI/blob/main/vibematcher.png)

---

## 📍 **Project Overview**

**Vibe Matcher** is an AI-driven fashion recommendation prototype that interprets user *mood* or *“vibe”* queries and matches them to the most relevant fashion products.  
Unlike standard keyword searches, this system uses **semantic-style embeddings** and **contextual understanding** to identify products aligned with a user’s emotional or stylistic intent.  

This prototype simulates a next-generation **AI recommendation pipeline** that can be integrated into e-commerce platforms for intelligent, human-like shopping experiences.

---

## 🎯 **Objective**

The aim of this project is to design a **mini AI recommendation system** that can:

1. 🧠 Interpret human-style vibe queries such as **“energetic urban chic”**.  
2. 🎨 Match and rank the **top-3 products** using similarity-based scoring.  
3. 🔍 Handle **edge cases** with intelligent query expansion.  
4. ⚡ Evaluate **system latency and accuracy**.  

---

## ⚙️ **Technical Workflow**

1. **Load Dataset:** Uses a mock JSON dataset (`fashion-product-data_json.json`) of 25 products with names, descriptions, vibe tags, and prices.  
2. **Generate Embeddings:** Creates **simulated 1536-dimensional embeddings** for product descriptions.  
3. **Query Expansion:** Enriches the user’s query with semantic synonyms for better context understanding.  
4. **Similarity Scoring:** Calculates **cosine similarity** between the query and product embeddings.  
5. **Multi-Modal Fusion:** Combines similarity, tag overlap, and price proximity for a balanced score.  
6. **Ranked Results:** Displays **top-3 matching products** with quality tags (`Excellent`, `Good`, `Fair`) and latency metrics.  

---

## 🚀 **Key Features & Innovations**

### 🧩 **1. Contextual Query Expansion**  
Expands user queries through a **semantic mapping** system to interpret mood-based terms naturally.  

> Example:  
> - `"urban"` → `["city", "street", "modern"]`  
> - `"cozy"` → `["warm", "comfortable", "snug"]`  

This allows the system to **bridge human vocabulary** with product catalog data and improve recall accuracy.

---

### ⚖️ **2. Multi-Modal Fusion Scoring**  
A novel **three-dimensional scoring system** combining:  
- **Semantic Similarity** — Vector-based cosine similarity  
- **Vibe Tag Overlap** — Matching contextual descriptors  
- **Price Affinity** — Penalizes large price differences  

This makes recommendations more **context-aware, user-friendly, and realistic** — closer to how humans think about “fit.”

---

## 📊 **Evaluation Metrics**

| **Metric** | **Description** |
|-------------|----------------|
| 🕒 **Latency (ms)** | Measures system response time per query |
| ✅ **Success Rate (>0.7)** | Percentage of queries with strong matches |
| 🧾 **Top-3 Product Ranking** | Displays ranked products with quality tags |

---

## 📘 **Future Improvements**

- Integrate **OpenAI Embeddings** (`text-embedding-ada-002`) for real semantic similarity.  
- Use **vector databases** like Pinecone or Weaviate for fast retrieval.  
- Add **personalization** with user behavior and preference tracking.  
- Introduce **multi-modal recommendation** combining text + image embeddings (e.g., CLIP).  

---

## 🏁 **Summary**

**Vibe Matcher** demonstrates how even a compact AI system can combine **semantic reasoning, contextual understanding, and fusion-based scoring** to produce meaningful, human-like fashion recommendations.  
It encapsulates the **creative essence of AI** — turning words like *“cozy autumn vibes”* into smart, emotional, and personalized product matches.  

---

**Repository:** [VibeMatcher-Nexora-AI](https://github.com/thevedantt/VibeMatcher-Nexora-AI)
