# 🧠 Clustering & DBSCAN — A Learning Journey  

**Author:** Yazdan Ghanavati  
📍 Master's Student, ICT for Internet and Multimedia — University of Padova  
🔗 [LinkedIn](https://www.linkedin.com/in/yazdan-ghanavati/) • 💻 [GitHub](https://github.com/Yazdan-Ghanavati)  

---

## 🧾 Overview  

This repository documents my **open learning journey** into clustering algorithms — starting from basic intuition to the practical implementation of **K-Means** and **DBSCAN**.  
The goal is not only to build working code, but to **teach through exploration**, helping others understand the concepts step by step.  

Each concept is implemented in a single Jupyter Notebook (`DBSCAN_mini_series.ipynb`), with detailed markdown explanations and saved visuals inside the `/imgs` folder.


---

## 🧩 Project Roadmap  

| # | Section | Status | Focus |
|---|----------|--------|--------|
| 1 | Why Clustering? | ✅ | Understanding why we group unlabeled data |
| 2 | K-Means Basics | ⬜ | How K-Means forms clusters iteratively |
| 3 | K-Means Failures | ⬜ | Why K-Means struggles on complex data |
| 4 | DBSCAN Intuition | ⬜ | Core, border, and noise points visually explained |
| 5 | Cluster Expansion | ⬜ | How DBSCAN grows clusters from dense regions |
| 6 | Tuning ε & MinPts | ⬜ | Finding the right parameters |
| 7 | DBSCAN vs K-Means | ⬜ | Comparing both approaches and summarizing insights |

----

## 🧩 Results & Reflection  


### 1️⃣ Why Clustering?  

The first part of this project focuses on a simple but fundamental question:  
**why do we cluster data?**

Clustering is the process of grouping similar data points when no labels are provided —  
it helps us reveal hidden structure and meaning inside complex datasets.  

To visualize this idea, I generated a random dataset with four hidden groups.  
Below, the **left plot** shows how the raw, unlabeled data initially looks like random noise.  
The **right plot**, after applying a simple clustering algorithm, reveals the underlying groups —  
showing how unsupervised learning can transform chaos into insight.  

<p align="center">
  <img src="imgs/why_clustering.png" width="700">
</p>

This simple example demonstrates the beauty of clustering:  
without knowing any labels, we can still discover meaningful organization in the data.  
That’s the foundation of many modern applications —  
from customer segmentation and image recognition to medical pattern discovery.  

In the next stage, we’ll dive deeper into **K-Means**,  
understanding exactly *how* it finds these clusters, and *why* it sometimes fails —  
paving the way toward more flexible methods like **DBSCAN**.

---

## ⚙️ How to Run  

1. **Clone the repository**  
   Use Git to copy the project locally and move into its folder:  

   git clone https://github.com/<your-username>/clustering-dbscan-mini.git  
   cd clustering-dbscan-mini  

2. **Create and activate a virtual environment**  
   It’s best practice to isolate dependencies:  

   • macOS / Linux → `python -m venv .venv && source .venv/bin/activate`  
   • Windows → `python -m venv .venv && .venv\Scripts\activate`  

3. **Install dependencies**  
   Install all required libraries listed in `requirements.txt`:  

   pip install -r requirements.txt  

4. **Run the notebook**  
   Launch Jupyter and open the main notebook:  

   jupyter notebook DBSCAN_mini_series.ipynb  

🖼️ Figures will be saved automatically to the `/imgs` folder after each run.


---


## 🧠 Notes  

- This notebook is being updated progressively as new sections are completed.  
- Each section corresponds to a short **LinkedIn post** that explains clustering intuitively.  
- The repository serves as both a **learning resource** and a **portfolio artifact** demonstrating professional documentation and reproducible code.  

---

## 🧾 How to Cite This Work  

If you find this notebook useful or wish to reference it in your own work, please cite it as follows:  

**Yazdan Ghanavati.** *Clustering & DBSCAN — A Learning Journey.*  
GitHub Repository, 2025. Available at: https://github.com/<your-username>/clustering-dbscan-mini  

You may also include the following BibTeX entry for academic use:  

@misc{ghanavati2025clustering,  
  author       = {Yazdan Ghanavati},  
  title        = {Clustering & DBSCAN — A Learning Journey},  
  year         = {2025},  
  publisher    = {GitHub},  
  journal      = {GitHub repository},  
  howpublished = {\url{https://github.com/<your-username>/clustering-dbscan-mini}},  
  note         = {Open learning project on clustering algorithms}  
}  

---

📩 *If you found this helpful, feel free to connect or share your feedback on LinkedIn — learning is always better together!* 🚀


---
