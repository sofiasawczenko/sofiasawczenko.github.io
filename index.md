## Selected Projects on Data

---

### Autonomous robot with a navigation system based on computer vision

This project integrates computer vision and robotics to create an autonomous robot for navigation on streets using Python, C, OpenCV, Flask, and GPIO libraries for image processing, motor control, and web-based interaction, with a Raspberry Pi handling vision and logic, and an Arduino managing motor control.

<img src= 'https://github.com/sofiasawczenko/sofiasawczenko.github.io/blob/master/images/object_detection2.jpg?raw=true'/>

This project demonstrates the use of OpenCV for lane detection on street images. The goal is to process the image, detect edges using the Canny edge detector, apply a mask to focus on the region of interest, and then extract the lane boundaries.

![image](https://github.com/user-attachments/assets/8391d225-290a-4701-b47b-0afd5561897b)

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-white?logo=Jupyter)](#) [![](https://img.shields.io/badge/RaspberryPi-white?logo=raspberrypi&logoColor=A22846)](#) [![](https://img.shields.io/badge/Arduino-white?logo=Arduino&logoColor=00878F)](#) [![](https://img.shields.io/badge/C/C++-white?logo=Cplusplus&logoColor=00599C)](#)

[View code on Github](https://github.com/sofiasawczenko/autonomous_robot_computer_vision)

---

### Building a Cricket Statistics Pipeline with Google Cloud Services

A comprehensive cricket statistics pipeline built using Google Cloud services. The pipeline involves retrieving data via the Cricbuzz API, and leveraging various cloud technologies such as Cloud Composer, Cloud Storage, Cloud Functions, Dataflow, and more to process and manage the data efficiently.

![image](https://github.com/user-attachments/assets/dddde745-1ff4-4fdd-85ae-2cb1d8edd0e8)

- **Data Retrieval with Python and Cricbuzz API:** Use Python to fetch cricket statistics efficiently via the Cricbuzz API.
- **Storing Data in Google Cloud Storage (GCS):** Save retrieved data as CSV files in GCS for secure, scalable storage.
- **Creating a Cloud Function Trigger:** Set up a Cloud Function to activate on file uploads in GCS, initiating the data pipeline.
- **Execution of the Cloud Function:** Design Cloud Function code to trigger and parameterize a Dataflow job seamlessly.
- **Dataflow Job for BigQuery:** Transfer data from GCS CSV files to BigQuery using a Dataflow job with optimized settings.
- **Looker Dashboard Creation:** Build a Looker dashboard linked to BigQuery for visualizing cricket statistics.

[![](https://img.shields.io/badge/Python-white?logo=Python)](#)

[View code on Github](https://github.com/sofiasawczenko/ETL_cricket_stats)

---

### Applying ETL to Sensitive Data with Google Cloud Services

Design and implement a data pipeline to extract employee data from multiple sources, mask sensitive information, and load the processed data into BigQuery. Additionally, create a secure dashboard to visualize the employee data. This ETL project utilizes Google Cloud Data Fusion for data extraction, Apache Airflow/Composer for orchestration, and Google BigQuery for data storage and analysis.

![image](https://github.com/user-attachments/assets/aae5098c-d72d-4d44-9a94-ca740674dabf)

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) 

[View code on Github](https://github.com/sofiasawczenko/ETL_employee_info_pipeline)

---

### Predicting Heart Failure with Supervised Learning Classification 
Heart failure is a serious medical condition that occurs when the heart is unable to pump enough blood to meet the body's needs. This can happen when the heart muscle becomes weakened or damaged, leading to a decrease in its ability to effectively pump blood.  In this project, I employed supervised learning, a method where a model learns from a labeled dataset. The output variable indicates whether a patient is susceptible to heart failure or not, often represented by classes like "at risk of heart failure" and "not at risk of heart failure".

<img src= 'https://github.com/sofiasawczenko/sofiasawczenko.github.io/blob/master/images/imagem_heart.png?raw=true'/>

This heart failure prediction project uses a Kaggle dataset, where several data preprocessing techniques were applied, followed by validations using methods like logistic regression, cross-validation, Naive Bayes, Random Forest, KNN and SVM.

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-white?logo=Jupyter)](#) [![](https://img.shields.io/badge/Anaconda-white?logo=anaconda)](#) [![](https://img.shields.io/badge/sklearn-white?logo=scikit-learn)](#) [![](https://img.shields.io/badge/Pandas-white?logo=pandas)](#) [![](https://img.shields.io/badge/Numpy-white?logo=numpy)](#) [![](https://img.shields.io/badge/Matplot-white?logo=Matplot)](#) 

[View code on Github](https://github.com/sofiasawczenko/heart_failure_forecasting)

---

### Predicting House Prices with Supervised Learning Regression
Real estate prices in Boston can be influenced by a multitude of factors, from location and size to local market trends. In this project, I utilized supervised regression learning, a technique where a model learns from labeled data and analyzes the relationship between variables for accurate predictions, considering factors like location, size, and market trends. The goal is to model this relationship and make precise estimations based on the data.

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-white?logo=Jupyter)](#) [![](https://img.shields.io/badge/Anaconda-white?logo=anaconda)](#) [![](https://img.shields.io/badge/Sklearn-white?logo=scikit-learn)](#)

[View code on Github](https://github.com/sofiasawczenko/forecasting_house_price/tree/main)

---

### Forecasting the weather in New York City with Supervised Learning Ridge Regression 
In this project, I employed Supervised Ridge Regression Learning to forecast weather patterns in New York City based on historical data from 1970 to 2022. Ridge regression is a variant of linear regression that introduces a regularization term to the model. This term helps prevent overfitting by penalizing overly complex models. By striking a balance between accuracy and simplicity, ridge regression proves invaluable in accurately predicting weather conditions based on historical data.

![image](https://github.com/user-attachments/assets/2268fbda-0328-4dc5-afea-8a2b80a9bc78)

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-white?logo=Jupyter)](#) [![](https://img.shields.io/badge/Anaconda-white?logo=anaconda)](#) [![](https://img.shields.io/badge/Sklearn-white?logo=scikit-learn)](#) [![](https://img.shields.io/badge/Pandas-white?logo=pandas)](#)

[View code on Github](https://github.com/sofiasawczenko/weather_forecasting/tree/main)

---

### Time Series Analysis for Vehicle Sales
In this project, using libraries like Pandas for tabular data visualization and manipulation, Matplotlib and Seaborn for constructing graphs, I analyzed the quantity of vehicle sales over a period of time. Given the significance of the time factor, I employed time series analysis to effectively quantify the growth and decline in sales.

<img src= 'https://github.com/sofiasawczenko/sofiasawczenko.github.io/blob/master/images/Captura%20de%20tela%202023-09-24%20162000.png?raw=true'/>

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-white?logo=Jupyter)](#) [![](https://img.shields.io/badge/Matplot-white?logo=Matplot)](#) [![](https://img.shields.io/badge/Seaborn-white?logo=seaborn)](#) [![](https://img.shields.io/badge/Pandas-white?logo=pandas)](#)

[View code on Github](https://github.com/sofiasawczenko/sales_time_series_analysis/tree/main)

---

### Preprocessing and Analyzing Text Sentiment with NLTK and TextBlob

Project that preprocess textual data using Python libraries such as NLTK, TextBlob, and Newspaper3k. It covers how to scrape articles, clean and process text data, and analyze its sentiment.

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) 

[View code on Github](https://github.com/sofiasawczenko/analyzing_text_sentiment)

---

### Flight Price Tracker with Selenium Automation

This project is a simple Python script that uses Selenium to scrape the price of a flight from a specific URL and save it to a .txt file. The script is also scheduled to run every two weeks using the schedule library.

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) 

[View code on Github](https://github.com/sofiasawczenko/get_flight_price_selenium)

---

### Web Scrapping Prices on Mercado Livre Marketplace

Marketplace Product Web Scraping with Python, BeautifulSoup, Requests, and SQLite Database.

![image](https://github.com/user-attachments/assets/5a068a6e-a509-443a-8bc0-89aa046ba0ed)

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) 

[View code on Github](https://github.com/sofiasawczenko/meli_webscraping)

---

### Unsupervised Learning Regression to predict Estimated Landing Time
The most common causes of flight delays are varied. While some are not related to accessible data, others are within reach. The inaccessible data will remain as noise caused from security, maintenance and disaster issues. The accessible data are weather and congestion that will shed some light to predict some of the flight delays

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) 

[View code on Github]()

---

### Unified Data Pipeline for Batch and Real-Time Amazon Product Reviews Analysis

Develop a data pipeline to process Amazon product review datasets, combining batch and streaming data sources. Batch data includes 82.83 million reviews and product metadata stored as JSON files in Azure Data Lake Storage. Streaming data provides real-time updates to ensure the dataset remains current. The pipeline will integrate these sources for efficient analysis and insights.
