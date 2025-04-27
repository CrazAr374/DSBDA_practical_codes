# 📚 DSBDA Practical Codes Repository

Welcome!  
This repository contains **all 10 practical codes** for the subject **Data Science and Big Data Analytics (DSBDA)** according to the **Savitribai Phule Pune University (SPPU)** syllabus.

---

## 📌 About DSBDA Subject (SPPU)

**Data Science and Big Data Analytics (DSBDA)** is a core subject designed to introduce students to the world of data analysis, machine learning, and handling big data.  
It covers essential techniques for **data preprocessing, visualization, machine learning algorithms, big data technologies**, and practical tools for real-world applications.

---

## 🛠️ Practical Codes Included

The repository contains Python codes for:
- Data wrangling and preprocessing
- Data visualization
- Regression models
- Classification models
- Clustering algorithms
- Association rule mining
- Introduction to Big Data tools (Hadoop, Spark)
- Working with NoSQL databases (MongoDB, Cassandra)

---

# 🧠 Theory Topics Covered

## 1. Data Wrangling
**Data wrangling** is the process of cleaning, transforming, and organizing raw data into a usable format.
It includes:
- Handling missing values
- Removing duplicates
- Correcting data types
- Normalization and standardization
- Creating new features (Feature Engineering)

**Importance**:  
Without proper wrangling, analysis or machine learning results can be inaccurate or misleading.

---

## 2. Data Visualization
**Data visualization** involves creating graphical representations of data to identify patterns, trends, and insights quickly.

Common Visualization Techniques:
- Histograms
- Scatter plots
- Box plots
- Heatmaps
- Line graphs
- Bar charts

**Importance**:  
Visualization makes complex data easier to understand and interpret for decision-making.

---

## 3. Regression
**Regression** is a supervised learning technique used to predict continuous outcomes.

Types of Regression:
- **Linear Regression**: Predicts output using a straight line.
- **Multiple Linear Regression**: Involves multiple input features.
- **Polynomial Regression**: Models nonlinear relationships.
- **Logistic Regression**: Used for classification, not continuous output.

**Applications**:
- Predicting prices
- Forecasting demand
- Risk assessment

---

## 4. Classification
**Classification** is a supervised learning method where the output variable is categorical (e.g., Yes/No, Spam/Not Spam).

Popular Classification Algorithms:
- Decision Trees
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Logistic Regression (for binary classification)

**Applications**:
- Email spam detection
- Disease diagnosis
- Credit scoring

---

## 5. Clustering
**Clustering** is an **unsupervised learning** technique where similar data points are grouped into clusters.

Popular Clustering Algorithms:
- K-Means Clustering
- Hierarchical Clustering
- DBSCAN

**Applications**:
- Customer segmentation
- Market research
- Image compression

---

## 6. Association Rule Mining
**Association Rule Mining** finds interesting relationships (associations) among a large set of data items.

Key Concepts:
- **Support**: Frequency of item occurrence.
- **Confidence**: Likelihood that item Y is bought when item X is bought.
- **Lift**: Increase in probability of Y given X.

**Applications**:
- Market Basket Analysis (e.g., "customers who buy bread also buy butter")
- Recommender Systems

Algorithms used:
- Apriori Algorithm
- FP-Growth Algorithm

---

## 7. Big Data Introduction
**Big Data** refers to extremely large datasets that are difficult to manage using traditional systems.

Characteristics (5 Vs of Big Data):
- **Volume**: Large amounts of data
- **Velocity**: Speed of data generation
- **Variety**: Different forms of data (text, images, videos)
- **Veracity**: Uncertainty in data
- **Value**: Usefulness of data

**Importance**:  
Organizations use big data to gain insights, innovate, and improve efficiency.

---

## 8. Hadoop Ecosystem
**Hadoop** is an open-source framework for distributed storage and processing of big data.

Core Components:
- **HDFS (Hadoop Distributed File System)**: For storing large datasets
- **MapReduce**: Programming model for processing large datasets
- **YARN**: Resource management layer

Additional Tools:
- Hive
- Pig
- HBase

---

## 9. Apache Spark
**Apache Spark** is an open-source unified analytics engine for big data processing, with built-in modules for streaming, SQL, machine learning, and graph processing.

**Why Spark over Hadoop MapReduce?**
- Faster processing (in-memory computation)
- Easy to use APIs
- Support for batch and real-time processing

---

## 10. NoSQL Databases
**NoSQL databases** are used to store unstructured or semi-structured data.

Types of NoSQL Databases:
- **Document-Oriented** (MongoDB)
- **Key-Value Stores** (Redis)
- **Column-Oriented** (Cassandra)
- **Graph-Based** (Neo4j)

**Advantages**:
- High scalability
- Flexibility in data storage
- Faster access for large-scale applications

---

# ⚡ How to Run the Practical Codes

```bash
# Clone this repository
git clone <repository_link>

# Navigate to the project directory
cd dsbda-practicals

# Install necessary libraries
pip install pandas numpy matplotlib seaborn scikit-learn plotly

# Open the Jupyter Notebook (.ipynb) files
jupyter notebook
```
