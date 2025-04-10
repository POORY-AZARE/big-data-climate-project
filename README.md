# big-data-climate-project
# Reddit Climate Change Analysis 🚀

This project uses Apache Spark and MongoDB to analyze large-scale Reddit posts related to climate change. The goal is to extract meaningful insights from unstructured social media data using Big Data technologies.

---

## 📁 Dataset

- Source: [Kaggle - Reddit Climate Change Dataset](https://www.kaggle.com/datasets/pavellexyr/the-reddit-climate-change-dataset)
- Size: 620,000+ Reddit posts
- Format: CSV

---

## 🔧 How to Run the Project

1. Install Requirements
   - Python 
   - Apache Spark
   - MongoDB (local)
   - Jupyter Notebook / VS Code
   - Install required Python packages:
    
     pip install pandas pymongo matplotlib seaborn
     
2. Step-by-Step

   - Load and clean dataset with Pandas
   - Store cleaned data into MongoDB using pymongo
   - Process data using PySpark
   - Run Spark SQL & MongoDB queries
   - Compare performance
   - Visualize key insights

3. MongoDB Setup
   - Run MongoDB locally on default port 27017
   - No authentication required
   - Collections are automatically created via script

---

## 📊 Notebooks

- 01_data_cleaning_and_mongodb.ipynb: Load and store data in MongoDB
- 02_spark_analysis.ipynb: Run PySpark transformations and queries
- 03_query_comparison.ipynb: Compare Spark SQL with MongoDB Aggregation
- 04_visualizations.ipynb: Data visualizations

---

## 👨‍💻 Team Members

- Poorya Zare Janakbari
- Nastaran Dehnavi
- Charity Kabutbei 
- Qiaoqiao Zou
- Roan Kessels

---

## ✅ Contributions

Contributions from all team members are visible via GitHub commits and notebook sections. Each notebook includes inline comments for clarity and attribution.

---

## 📌 License

This project is for academic use only – part of the Big Data Pipeline Course 2025.