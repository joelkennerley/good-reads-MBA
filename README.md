# Good Reads Market basket analysis

This project was completed as part of my DATA301 coursework. It focuses on uncovering associations between book interactions using market basket analysis on a large-scale Goodreads dataset.

# 🔍 Project Overview
The goal of this project was to identify frequently co-occurring book interactions using the Apriori algorithm. To handle the scale of the dataset efficiently, I used Dask for parallel processing and tested the scalability of the solution using Google Cloud.

# ⚙️ Technologies Used

Python

Dask – for scalable, parallelized data processing

Google Cloud Platform (GCP) – for deployment and scalability testing

Jupyter Notebooks – for development and visualization

# 🗃️ Dataset
The first dataset contains user interaction data from Goodreads, including book views, ratings, and user behaviors. Due to privacy and size restrictions, the raw dataset is not included in this repository. The second data set contains book meta data, which is required to extract infomation on books, specifically the titles.

# 🚀 Features
Efficiently processes large-scale interaction data using Dask

Applies Apriori to find frequent itemsets and generate association rules

Evaluates scalability by deploying and running the analysis on GCP
