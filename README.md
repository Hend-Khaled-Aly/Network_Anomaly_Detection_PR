  # **Network Anomaly Detection using Clustering**

This project was developed as part of the **Pattern Recognition (CC484)** course at the **Faculty of Engineering, Alexandria University**.

## 📖 Overview
The aim of this project is to detect network anomalies using unsupervised clustering methods. We applied **K-Means**, **Normalized Cut**, and **DBSCAN** algorithms to the **KDD Cup 1999** dataset — a standard dataset for intrusion detection tasks.

## 📂 Contents
- **Jupyter Notebook**: Full implementation including data preprocessing, clustering, and evaluation.
- **Project Report**: Detailed explanation of the methodology, results, and evaluation metrics.

## 🔧 Key Features
- **Preprocessing**: Converted categorical features to numerical.
- **K-Means Clustering**: Tested across multiple values of K (7, 15, 23, 31, 45).
- **Normalized Cut**: Custom implementation using reduced dataset size.
- **DBSCAN**: Explored density-based clustering and compared its performance.
- **Evaluation Metrics**: Precision, Recall, F1-Score, and Conditional Entropy were used to assess anomaly detection performance.

## 📊 Dataset
- **Source**: [KDD Cup 1999 Dataset]
(https://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html)
- **Files Used**:
  - `kddcup.data.gz` (Training)
  - `corrected.gz` (Testing)

## 📎 Note
This repository contains the notebook and report only. For full details, refer to the included PDF report.
