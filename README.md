# Quantum-inspired-optimization-Single-cell-clustering
# 🧬 Quantum-Inspired Single-Cell Clustering

A project combining **AI, optimization, and genomics** to cluster single-cell RNA sequencing data using **quantum-inspired techniques**.

---

## 🚀 Overview

We reformulate clustering as a **QUBO (Quadratic Unconstrained Binary Optimization)** problem and solve it using **simulated annealing**.

Instead of traditional clustering:

* We treat clustering as an optimization problem
* We explore multiple valid clustering solutions

---

## ⚛️ Key Idea

> "Clustering = Optimization Problem"

We:

1. Build a cell-cell similarity graph
2. Convert clustering into a QUBO problem
3. Solve using simulated annealing
4. Compare with classical methods

---

## 🧪 Methods Used

* **Scanpy** → preprocessing
* **PCA + UMAP** → dimensionality reduction
* **QUBO formulation** → optimization problem
* **Simulated Annealing (dimod)** → quantum-inspired solver
* **KMeans & Leiden** → classical baselines

---

## 📊 Results

| Method           | Silhouette Score |
| ---------------- | ---------------- |
| Quantum-Inspired | 0.13             |
| KMeans           | 0.21             |
| Leiden           | 0.20             |

### 💡 Insight

Quantum-inspired optimization produces **multiple valid solutions**, revealing alternative biological structures.

---

## ⚠️ Limitation

* QUBO grows quadratically → limited to ~50 cells
* Simulation used instead of real quantum hardware

---

## 🖥️ Dashboard

Interactive UI included:

👉 Open:

```
dashboard/index.html
```

---

## 📂 How to Run

### Option 1: Google Colab

Open:

```
quantum_clustering_project.ipynb
```


```

---

## 🧠 Contribution

This project demonstrates:

* QUBO-based clustering
* Quantum-inspired optimization
* Comparison with classical ML

---



---
