# Big Data Analytics with PySpark — Project Walkthrough

This repository contains two major Big Data projects implemented using **Python** and **PySpark**.  
The work focuses on handling **large datasets**, performing **distributed analytics**, and applying **machine learning at scale**.

---

## 📊 Project 1: Rwanda Household Survey Analysis

In this project, a **large household survey dataset (~3GB)** from Rwanda was analyzed to demonstrate scalable data processing.

### What was done
- Loaded the dataset using **Pandas** and **PySpark** to compare execution time.
- Observed that **PySpark is more efficient** for large datasets.
- Performed distributed data analysis using Spark DataFrames.

### Key analyses
- Household counts by **province** and **urban/rural status**
- Average **age** by province
- **Gender distribution** across districts
- **Literacy rates** by language
- **Household size** analysis
- Education level distribution
- Identification of **multilingual households**
- Occupation patterns by province
- Data quality checks (missing values)

### Key takeaway
PySpark enables efficient analysis of large national survey data that would be slow or memory-intensive using traditional tools like Pandas.

---

## 🎵 Project 2: Music Genre Classification (Machine Learning)

This project applies **machine learning** to classify songs into **23 music genres** using extracted audio features.

### What was done
- Loaded and explored a high-dimensional music dataset.
- Performed exploratory data analysis on features such as:
  - Energy
  - MFCCs
  - BPM
  - Spectral features
- Applied feature scaling and feature selection.
- Trained and evaluated multiple models using **PySpark ML**:
  - Logistic Regression
  - Multilayer Perceptron
  - Random Forest (best performing)

### Results
- Random Forest achieved the highest accuracy among tested models.
- Results indicate potential improvement with further tuning or more data.

### Key takeaway
PySpark ML allows scalable training and evaluation of machine learning models on large datasets.

---

## ✅ Overall Summary

So far, this work demonstrates:
- Large-scale data ingestion
- Distributed data cleaning and analysis
- Performance comparison between Pandas and PySpark
- End-to-end machine learning workflows using PySpark

**Pipeline covered:**  
Data loading → Cleaning → Analysis →
