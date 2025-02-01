---
layout: post
title: "My Data Science Journey"
subtitle: "A glimpse into the projects and skills I've developed"
cover-img: /assets/img/background.png
thumbnail-img: /assets/img/portfolio-thumb.png
share-img: /assets/img/portfolio-cover.jpg
tags: [data science, projects, Python, R, SQL, Machine Learning]
author: Nhi NGUYEN
---

As a **Data Science student at CY Tech**, I’ve developed a passion for using data to solve real-world problems, uncover insights, and drive decision-making. Here’s a selection of the projects that showcase my journey and growth as a data scientist.

### Project 1: **Houses in Melbourne**
**Description:**  
This project involved analyzing real estate data to predict house prices in Melbourne. Using **Pandas**, **Matplotlib**, and **Seaborn**, I explored trends, cleaned the dataset, and created visualizations to identify key factors influencing house prices.

**Tech Stack:** Python, Pandas, Matplotlib, Seaborn
![Image 1](/assets/img/1.png)
![Image 2](/assets/img/2.png)
[🔗 View Project on GitHub](https://github.com/yourusername/melbourne-houses)

---

### Project 2: **Data Wrangling – Preprocessing PhD Dataset**
**Description:**  
For this project, I worked with a **PhD dataset** containing over 480,000 entries of students who defended their PhDs in France between 1985 and 2020. My goal was to explore issues like missing or unreliable data, generate graphs to visualize data quality issues, and use the **UpSet** package to analyze missing data patterns.

**Tech Stack:** Python, Pandas, UpSet, Data Cleaning
![Image 3](/assets/img/3.png)
*Create a graph to visualize the distribution of missing data within the dataset.*
![Image 4](/assets/img/4.png)
*Analyze the missing data patterns using the UpSet package.*
[🔗 View Project on GitHub](https://github.com/yourusername/phd-data-wrangling)

---

### Project 3: **Dimensional Reduction & Clustering**
**Description:**  
This project involved analyzing a **user profile dataset** from a data app to perform **dimensional reduction** and **clustering**. I used **PCA** to visualize quantitative variables and **MCA** to represent qualitative data, as well as applied clustering techniques to group similar profiles based on various features.

**Tech Stack:** Python, Pandas, PCA, MCA, Clustering, R

![Image 5](/assets/img/5.png)
*Represent the different quantitative data using a PCA.*
![Image 6](/assets/img/6.png)
*Represent qualitative variables that make up this dataset in a factorial plan using a MCA.*
![Image 7](/assets/img/7.png)
*Visualize PCA results: Scree plot to show variance explained by each principal component.*
![Image 8](/assets/img/8.png)
*Visualize the clusters in PCA space.*

[🔗 View Project on GitHub](https://github.com/yourusername/dimensional-reduction-clustering)

---

### Project 4: **Iris Dataset - PCA and Clustering**
**Description:**  
In this project, I analyzed the **Iris dataset**, which includes measurements of iris flowers. I used **PCA** to reduce the dimensionality of the dataset and created a **scree plot** to determine the number of dimensions to keep for analysis. I also visualized clusters in the PCA space.

**Tech Stack:** R, Scikit-learn, PCA
![Image 9](/assets/img/9.png)  
*Represent PCA with Standardization.*
![Image 10](/assets/img/10.png)  
*Represent these correlations in the form of a correlogram of your choice (eg, with bubbles and colors).*
![Image 11](/assets/img/11.png) 
*PCA graph of variables.*
![Image 12](/assets/img/12.png)  
*Use the elbow method on a ”scree plot” to assess how many dimensions to keep in subsequent analyses.*
![Image 13](/assets/img/13.png)  
*Circle of Correlation based on cos2*
![Image 14](/assets/img/14.png)  
*Individuals on Factorial Plane based on cos2*
![Image 15](/assets/img/15.png)  
*K-Means clustering in PCA space*
![Image 16](/assets/img/16.png)  
*Elbow Method*
![Image 17](/assets/img/17.png)  
*Split-Stick Method*
![Image 18](/assets/img/18.png) 
*Silhouette Method*

[🔗 View Project on GitHub](https://github.com/yourusername/iris-pca-clustering)

---

### Project 5: **Tinder Messages Analysis**
**Description:**  
This project involved analyzing **Tinder conversation data** to identify patterns in message types (e.g., questions, affirmations, politeness). I used **sequence plots** and **heatmaps** to visualize message trends and applied **Traminer clustering** to analyze sequences of messages.

**Tech Stack:** R, Data Visualization, Clustering
![Image 19](/assets/img/19.png)  
*Sequence plot.*
![Image 20](/assets/img/20.png)  
*Heat map.*
![Image 21](/assets/img/21.png)  
*Heat map. *
![Image 22](/assets/img/22.png)  
*Use traminer to cluster the sequences.*

[🔗 View Project on GitHub](https://github.com/yourusername/tinder-messages-analysis)

---

### Project 6: **Text Mining – PhD Dissertations**
**Description:**  
This project involved processing a dataset of **50 PhD dissertations** in PDF format. I converted the PDFs to text files, then applied **TF-IDF** and **cosine similarity** to assess document similarity. I also created a **forced directed graph** to visualize the strongest correlations between terms in the dissertations.

**Tech Stack:** Python, NLTK, TF-IDF, Cosine Similarity
![Image 23](/assets/img/23.png)  
*Similarity Matrix.*
![Image 24](/assets/img/24.png)  
*Cosine Similarity Distribution.*
![Image 25](/assets/img/25.png)  
*Forced Directed Graph on top 20 strongest correlations.*

[🔗 View Project on GitHub](https://github.com/yourusername/phd-text-mining)

---

### Project 7: **Machine Learning – Classification & Regression**
**Description:**  
This project covers various **machine learning tasks**, including classification and regression, applied to different datasets. It involves decision trees, Random Forest, kNN, and regression models for predictive analysis.  

---

#### **Penguins Classification**
**Goal:** Classify **penguin species** using culmen dimensions. A **decision tree** (depth = 1) was trained to understand feature importance.  
**Tech Stack:** Python, Scikit-learn, Decision Trees 
![Image 26](/assets/img/26.png)  
*Train a tree of depth 1.*
![Image 27](/assets/img/27.png)  
*Scatter plot.*
![Image 28](/assets/img/28.png)  
*Classification tree of depth 6.*

---

#### **Breast Cancer Detection**
**Goal:** Predict whether a tumor is **benign or malignant** using classification trees. The project also compares **Random Forest** and **kNN**, evaluating them with **ROC and Precision-Recall curves**.  
**Tech Stack:** Python, Scikit-learn, Decision Trees, Random Forest, kNN  
![Image 29](/assets/img/29.png)  
*Confusion matrix – Random Forest.*
![Image 30](/assets/img/30.png)  
*Confusion matrix – kNN.*
![Image 31](/assets/img/31.png)  
*Display ROC curves and the corresponding AUCs.*
![Image 32](/assets/img/32.png)  
*Display a Precision-Recall curve and the corresponding AUC P-R. *


---

#### **Baseball Performance Prediction**
**Goal:** Predict the **number of wins per season** based on baseball performance metrics (e.g., runs scored, OBP, SLG). Regression models were trained, and predictions were visualized with scatterplots.  
**Tech Stack:** Python, Scikit-learn, Regression, Data Visualization  

![Image 33](/assets/img/33.png)
*Predict the response on the test data set, and make a scatterplot with predicted data, and actual data.*
![Image 34](/assets/img/34.png)  
*Pairwise Correlation.*

