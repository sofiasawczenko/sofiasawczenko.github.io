## Selected Data Projects

---

### Autonomous robot with a navigation system based on computer vision

This project integrates computer vision and robotics to create an autonomous robot for navigation on streets using Python, C, OpenCV, Flask, and GPIO libraries for image processing, motor control, and web-based interaction, with a Raspberry Pi handling vision and logic, and an Arduino managing motor control.

<img src= 'https://github.com/sofiasawczenko/sofiasawczenko.github.io/blob/master/images/object_detection2.jpg?raw=true'/>

This project demonstrates the use of OpenCV for lane detection on street images. The goal is to process the image, detect edges using the Canny edge detector, apply a mask to focus on the region of interest, and then extract the lane boundaries.

![image](https://github.com/user-attachments/assets/8391d225-290a-4701-b47b-0afd5561897b)

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-white?logo=Jupyter)](#) [![](https://img.shields.io/badge/RaspberryPi-white?logo=raspberrypi&logoColor=A22846)](#) [![](https://img.shields.io/badge/Arduino-white?logo=Arduino&logoColor=00878F)](#) [![](https://img.shields.io/badge/C/C++-white?logo=Cplusplus&logoColor=00599C)](#) [![](https://img.shields.io/badge/openCV-white?style=flat&logoColor=000000&color=ffffff)](#)

[View code on Github](https://github.com/sofiasawczenko/autonomous_robot_computer_vision)

---

### Chatbot with RAG using LangChain and OpenAI

This project showcases the development of a console-based chatbot leveraging Retrieval-Augmented Generation (RAG), powered by LangChain and OpenAI’s large language model. RAG is a powerful technique that combines traditional retrieval methods with generative AI, enabling the chatbot to provide highly relevant and context-aware responses.

In this implementation, the system scans and indexes a collection of PDF documents stored locally. When a user asks a question, the chatbot retrieves relevant information from the indexed PDFs and feeds it into the language model, allowing it to generate accurate and contextually grounded answers.
  Key components and features include:
  
  - LangChain for chaining components like retrievers, language models, and memory.
  
   - OpenAI API for natural language understanding and generation.
  
  - PDF loaders for parsing and processing local documents.
  
  - Vector stores to embed and search relevant chunks of text.
  
  - Designed for terminal use, making it lightweight and easy to deploy.

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) 

[View code on Github](https://github.com/sofiasawczenko/ETL_cricket_stats)


---

### Building a Cricket Statistics Pipeline with Google Cloud Services

Develop a comprehensive cricket statistics pipeline leveraging Google Cloud services for efficient data processing and visualization. The pipeline begins with data retrieval from the Cricbuzz API, storing the data securely as CSV files in Google Cloud Storage (GCS), which provides scalable and durable storage for large datasets. A Cloud Function is configured to automatically trigger upon file uploads in GCS, initiating the pipeline by seamlessly passing parameters to a Dataflow job. This Dataflow job processes and loads the data into BigQuery, a fully-managed, serverless data warehouse designed for fast and scalable analytics. Finally, a Looker Studio dashboard connects to BigQuery, enabling real-time visualization and analysis of the cricket statistics.

![image](https://github.com/user-attachments/assets/512d885d-79c7-4b4f-b3ac-5ee706521dad)

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Google_Cloud-white?style=flat&logo=google-cloud&logoColor=4285F4)](#) [![](https://img.shields.io/badge/Cloud_Composer-white?style=flat&logoColor=000000&color=ffffff)](#) [![](https://img.shields.io/badge/Cloud_Storage-white?style=flat&logoColor=000000&color=ffffff)](#) [![](https://img.shields.io/badge/Cloud_Functions-white?style=flat&logoColor=000000&color=ffffff)](#) [![](https://img.shields.io/badge/Dataflow-white?style=flat&logoColor=000000&color=ffffff)](#) [![](https://img.shields.io/badge/Big_Query-white?style=flat&logoColor=000000&color=ffffff)](#) [![](https://img.shields.io/badge/Looker-white?style=flat&logoColor=000000&color=ffffff)](#)

[View code on Github](https://github.com/sofiasawczenko/ETL_cricket_stats)

---

### ETL Pipeline for Sensitive Employee Data with Google Cloud Services

Develop a secure and efficient ETL pipeline to process sensitive employee data from various sources. Use Google Cloud Data Fusion for seamless data extraction, applying data masking techniques to protect sensitive information. Leverage Apache Airflow/Cloud Composer for orchestrating data workflows, ensuring smooth and automated processing. Load the sanitized data into BigQuery, a robust, serverless data warehouse designed for secure and scalable analytics. Finally, create an interactive and secure dashboard for visualizing employee data, enabling insightful and privacy-compliant reporting.

![image](https://github.com/user-attachments/assets/09204ad4-646e-4b83-8f57-377e0b507754)

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Google_Cloud-white?style=flat&logo=google-cloud&logoColor=4285F4)](#)  [![](https://img.shields.io/badge/Cloud_storage-white?style=flat&logoColor=000000&color=ffffff)](#) [![](https://img.shields.io/badge/Cloud_Data_Fusion-white?style=flat&logoColor=000000&color=ffffff)](#) [![](https://img.shields.io/badge/Big_Query-white?style=flat&logoColor=000000&color=ffffff)](#) [![](https://img.shields.io/badge/Looker-white?style=flat&logoColor=000000&color=ffffff)](#) 


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

[![](https://img.shields.io/badge/Python-white?logo=Python)](#)  [![](https://img.shields.io/badge/NLTK-white?style=flat&logo=sqlite&color=ffffff)](#)  [![](https://img.shields.io/badge/TextBlob-white?style=flat&logo=sqlite&color=ffffff)](#)  [![](https://img.shields.io/badge/Newspaper3k-white?style=flat&logo=sqlite&color=ffffff)](#)

[View code on Github](https://github.com/sofiasawczenko/analyzing_text_sentiment)

---

### Flight Price Tracker with Selenium Automation

This project is a Python script that uses Selenium to scrape the price of a flight from a specific URL and save it to a .txt file. The script is also scheduled to run every two weeks using the schedule library.

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Selenium-white?style=flat&logoColor=000000&color=ffffff)](#)  [![](https://img.shields.io/badge/Schedule-white?style=flat&logoColor=000000&color=ffffff)](#)

[View code on Github](https://github.com/sofiasawczenko/get_flight_price_selenium)

---

### Web Scraping Marketplace Prices on Mercado Livre

Develop a web scraping solution to extract product prices and details from the Mercado Livre marketplace using Python, BeautifulSoup, and Requests. Store the scraped data efficiently in an SQLite database for easy access and analysis, enabling tracking of marketplace trends and price changes over time.

![image](https://github.com/user-attachments/assets/72d6fdf8-2c70-4f46-826c-24c20d5f2af9)


[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/SQLite-white?style=flat&logo=sqlite&logoColor=000000&color=ffffff
)](#) [![](https://img.shields.io/badge/BeautifulSoup-white?style=flat&logoColor=000000&color=ffffff)](#) [![](https://img.shields.io/badge/Requests-white?style=flat&logoColor=000000&color=ffffff)](#)

[View code on Github](https://github.com/sofiasawczenko/meli_webscraping)

---

### Unsupervised Learning Regression to predict Estimated Landing Time
The most common causes of flight delays are varied. While some are not related to accessible data, others are within reach. The inaccessible data will remain as noise caused from security, maintenance and disaster issues. The accessible data are weather and congestion that will shed some light to predict some of the flight delays

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) 

[View code on Github]()

---

### Virtual Assistant in Browser Extension

A virtual assistant powered by artificial intelligence, seamlessly integrated into the browser as an extension. This assistant provides real-time, context-aware support to users while they browse, offering personalized help and insights based on on-screen content and user interactions.

The assistant utilizes the Google Gemini API for natural language processing and understanding, enabling it to interpret queries, provide intelligent responses, and enhance the browsing experience without the need to switch tabs or applications.

Key highlights:

- Integrated directly into the browser interface for instant accessibility.

- Uses Google Gemini API for real-time AI-powered communication.

- Ideal for research support, productivity boosts, and context-driven interactions.

- Modular design for future expansion to other APIs or use cases.
