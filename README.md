# 🤖 Intelligent Customer Segmentation

> Ein Data-Science-Projekt zur automatisierten Kundensegmentierung mittels Clustering-Algorithmen (K-Means & K-Medoids). Analyse von über 540.000 Datensätzen zur Optimierung von Marketingstrategien.

---

## 🖼️ Analyse-Visualisierung

![Clustering Result 1](segmentation_1.png)

![Clustering Result 2](segmentation_2.png)

![Clustering Result 3](segmentation_3.png)

![Clustering Result 4](segmentation_4.png)

![Clustering Result 5](segmentation_5.png)

*(Hinweis: Da die Original-.pbix-Datei archiviert wurde, dienen diese Screenshots und die beigefügte PDF-Dokumentation als Referenz für die visuelle Umsetzung.)*
---

## 📌 Projektübersicht

Dieses Projekt konzentriert sich auf die Anwendung von Machine Learning Techniken, um Kundenverhalten in einem E-Commerce-Kontext zu verstehen. Durch den Vergleich verschiedener Clustering-Ansätze wurden stabile Kundensegmente identifiziert.

**Kernaspekte des Projekts:**
- **Algorithmen:** Vergleich von K-Means und K-Medoids.
- **Datenvorverarbeitung:** Bereinigung, Feature Engineering und Min-Max-Skalierung.
- **Optimierung:** Bestimmung der optimalen Clusteranzahl (k) mittels Elbow-Method.
- **Business-Logik:** Interpretation der Segmente (z.B. Einmalkäufer, Stammkunden, Premium-Kunden).

---

## 📂 Datenbasis & Methodik

| Merkmal | Details |
|---|---|
| **Datenquelle** | Online Retail Dataset (Kaggle/UCI) |
| **Umfang** | > 540.000 Transaktionen |
| **Metriken** | Euklidische vs. Manhattan-Distanz |
| **Dokumentation** | Vollständige Analyse in `Intelligent Data Analysis.pdf` |

---

## 🛠️ Tech Stack

- **Python:** (Pandas, NumPy, Scikit-learn, Matplotlib)
- **Machine Learning:** Clustering (K-Means, K-Medoids)
- **Data Visualization:** Streudiagramme (Scatter Plots), Zentroden-Analyse

---

## 📁 Repository-Struktur
Intelligent-Customer-Segmentation/
│
├── README.md                          <- Projektbeschreibung
├── Intelligent Data Analysis.pdf      <- Detaillierter wissenschaftlicher Bericht
├── README Intelligent Customer Segmentation .pdf <- Zusammenfassung
└── segmentation_x.png                 <- Visualisierungen der Analyse

---

## 💡 Key Findings

- **K=6** wurde als optimale Clusteranzahl für geschäftliche Anwendungen identifiziert.
- **K-Medoids** erwies sich als robuster gegenüber Ausreißern (Outlier) im Vergleich zu K-Means.
- Die Segmente ermöglichen gezieltes Marketing und personalisierte Kundenansprache.

---

## 👩‍💻 Autorin

**Katarzyna Brzeski**
*Vizja Universität – Business Data Analysis*

---
*Projekt realisiert im Rahmen der Spezialisierung AI & Data Science · 2024*
