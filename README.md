# **Text Clustering Assignment**

This project implements a text clustering algorithm to group similar sentences based on various topics. The dataset contains 118,723 unique descriptions and the goal is to cluster these descriptions into meaningful groups using machine learning techniques.
Due to Rescource Limitations, the dataset used in the implementation in brought down to 30,000

## **1. Dataset**

The dataset used in this project consists of 118,723 unique descriptions. These descriptions represent a wide range of topics and form the basis for unsupervised clustering. The dataset is processed and vectorized to identify latent topics in the text.
You can download the dataset & extract them into the cloned repository folder
[Dataset](https://www.kaggle.com/datasets/amananandrai/ag-news-classification-dataset?select=train.csv)
### **Data Attributes**
- **Unique Descriptions**: 118,723 used only 30,000 due to resouce limitations.
- **Description Length**: Varies, with an average of 10-50 words per description.
- **Language**: English

## **2. Approach**

The approach to clustering involves the following key steps:

1. **Preprocessing**:
   - Tokenization and removal of stopwords.
   - Vectorization of text using Bag of Words.

2. **Clustering Algorithm**:
   - We used the K-Means algorithm to group the descriptions based on cosine similarity.
   - After vectorizing the text data, K-Means was applied to generate clusters of similar descriptions.
   - Since there are huge number of descriptions, it may take little long to complete the execution
3. **Evaluation**:
   - Clusters were analyzed qualitatively to assess the coherence of topics within each group.
   - The number of clusters can be adjusted for different granularity of topics.

## **3. Code Overview**

All code, including preprocessing, clustering, and analysis, is contained within a single Jupyter notebook.

- **text_clustering.ipynb**: This notebook includes data loading, preprocessing, clustering, and evaluation steps. All preprocessing functions, utility code, and clustering logic are implemented here.

### **Steps to Run the Notebook**

1. Clone the repository:
   ```bash
   git clone https://github.com/RajV95/text-clustering.git
