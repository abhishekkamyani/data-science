# Data Science notes by Abhishek Kamyani


## Introduction to Data Science
### What is Data Science?
Data Science is an interdisciplinary field that combines mathematics, statistics, programming, and domain knowledge to extract meaningful insights from data. It involves collecting, analyzing, visualizing, and making predictions using data.

### Why is Data Science Important?
- Data is generated in large volumes, requiring advanced techniques for processing and analysis.
- Businesses use data-driven insights to make informed decisions.
- Automates processes and enhances efficiency in various industries.
- Improves customer experience through personalized recommendations.
- Advances in healthcare enable early disease detection and drug discovery.

Data Science is crucial because it turns raw data into actionable insights, enabling better decision-making and solving complex problems. It helps predict trends, optimize processes, and drive innovations like personalized recommendations, fraud detection, and healthcare advancements, making businesses and societies more efficient and data-driven.

---

## Applications of Data Science
Data Science is used in almost every industry. Here are some key applications:

1. Healthcare: Predicting diseases, drug discovery, personalized medicine.
2. Finance: Fraud detection, risk management, stock market analysis.
3. E-commerce: Recommendation systems (e.g., Amazon, Netflix), customer segmentation.
4. Transportation: Route optimization, self-driving cars.
5. Social Media: Sentiment analysis, targeted advertising.
6. Sports: Player performance analysis, game strategy optimization.

---

## Prerequisites for Data Science
To become a data scientist, knowledge in the following areas is required:

### 1. Mathematics:
- Statistics: Mean, median, standard deviation, probability.
- Linear Algebra: Vectors, matrices (used in machine learning).
- Calculus: Derivatives, integrals (used in optimization).

### 2. Programming:
- Python or R (most commonly used languages).
- Libraries like Pandas, NumPy, Matplotlib, Scikit-learn.

### 3. Data Wrangling:
- Cleaning and preprocessing raw data (handling missing values, outliers).

### 4. Machine Learning:
- Supervised and unsupervised learning algorithms.

### 5. Domain Knowledge:
- Understanding the industry context (e.g., finance, healthcare).

---

## Data Scientist’s Work
A data scientist’s job involves the following tasks:

1. Data Collection: Gathering data from databases, APIs, or web scraping.
2. Data Cleaning: Removing errors, handling missing values, and preparing data for analysis.
3. Exploratory Data Analysis (EDA): Visualizing and summarizing data to identify patterns.
4. Model Building: Using machine learning algorithms to create predictive models.
5. Model Evaluation: Testing the model’s accuracy and improving it.
6. Deployment: Implementing the model into real-world applications.
7. Communication: Presenting insights to stakeholders using visualizations and reports.

A structured approach follows these steps: Collect → Clean → Analyze → Model → Evaluate → Deploy → Communicate.

---

## Life Cycle of Data Science
The data science life cycle consists of the following stages:

1. Problem Definition: Understanding the business problem and defining goals.
2. Data Collection: Gathering relevant data from various sources.
3. Data Cleaning: Preparing data for analysis by handling missing values, outliers, etc.
4. Exploratory Data Analysis (EDA): Analyzing data by visualizing and summarizing to find patterns.
5. Model Building: Selecting and training machine learning models.
6. Model Evaluation: Testing the model’s performance using metrics such as accuracy, precision, and recall, and improving it.
7. Deployment: Integrating the model into a production environment.
8. Monitoring & Maintenance: Ensuring the model performs well over time.

---

## Python for Data Science
### Why Python for Data Science?
1. Easy to Learn: Python has a simple and readable syntax, making it beginner-friendly.
2. Libraries and Frameworks: Python provides powerful libraries such as:
   - Pandas (data manipulation)
   - NumPy (numerical computations)
   - Matplotlib/Seaborn (data visualization)
   - Scikit-learn (machine learning)
3. Versatility: Python can be used for web development, automation, and more.
4. Community Support: Large community and extensive resources for learning.
5. Integration: Works well with big data tools such as Hadoop and Spark.

Understanding key libraries and their applications is essential: Pandas for data manipulation, NumPy for numerical operations, Matplotlib for visualization, and Scikit-learn for machine learning.

---

## Summary of Key Points
- Data Science involves transforming raw data into actionable insights using statistics, programming, and domain knowledge.
- Applications of Data Science span multiple industries, including healthcare, finance, and e-commerce.
- Prerequisites for Data Science include mathematics, programming, data wrangling, machine learning, and domain expertise.
- A data scientist follows a structured workflow: Collect → Clean → Analyze → Model → Evaluate → Deploy → Communicate.
- The Data Science Life Cycle includes problem definition, data collection, exploratory data analysis, model building, evaluation, deployment, and monitoring.
- Python is widely used in Data Science due to its simplicity, extensive libraries, versatility, and strong community support.

---



### **Definition of Data Engineering**  
Data Engineering focuses on the design, development, and maintenance of systems that allow for the efficient collection, storage, and processing of data. It involves building data pipelines, ensuring data quality, and optimizing databases for analytical use. It ensures that high-quality data is available for data science and analytics.

### **Data Engineering vs. Data Science**  

| Aspect            | Data Engineering | Data Science |
|------------------|----------------|-------------|
| **Definition**  | Develops and maintains data infrastructure for storage, processing, and accessibility. | Analyzes and interprets data to generate insights and predictions. |
| **Focus**  | Data collection, storage, transformation, and pipeline management. | Statistical analysis, machine learning, and decision-making. |
| **Key Skills**  | SQL, ETL (Extract, Transform, Load), Cloud Computing, Big Data Tools (Spark, Hadoop). | Python, Statistics, Machine Learning, Data Visualization. |
| **Output**  | Cleaned, structured, and accessible data for analysis. | Predictive models, insights, and reports for decision-making. |

---

# Data Collection Methods in Data Science

Data collection is the process of gathering information from various sources for analysis. It can be categorized into primary and secondary data collection methods.

## 1. Primary Data Collection (Direct Collection)
This involves gathering data firsthand, specifically for a study or project.

### A. Surveys & Questionnaires
- Used in market research, customer feedback, and academic studies.
- **Tools:** Google Forms, SurveyMonkey, Typeform.

### B. Interviews
- One-on-one discussions to gain detailed insights.
- **Types:** Structured, semi-structured, unstructured.

### C. Observations
- Recording real-world behaviors without direct interaction.
- **Used in:** User experience research, security monitoring, etc.

### D. Experiments & A/B Testing
- Controlled testing of hypotheses (e.g., testing two website versions).
- **Used in:** Marketing, product development, healthcare studies.

### E. IoT & Sensor Data Collection
- Data collected from smart devices, wearables, and industrial sensors.
- **Used in:** Smart cities, healthcare, manufacturing.

---

## 2. Secondary Data Collection (Existing Data Sources)
This involves collecting already existing data from external sources.

### A. Public Datasets & Open Data
- Government databases, research publications, and open data repositories.
- **Examples:** Kaggle, UCI Machine Learning Repository, Google Dataset Search.

### B. APIs (Application Programming Interfaces)
- Collecting real-time data from online services.
- **Examples:** Twitter API (for social media analysis), OpenWeather API (for weather data).

### C. Database Systems
- Extracting structured data from relational and non-relational databases.
- **Tools:** SQL (for structured databases), MongoDB (for NoSQL databases).

### D. Business & Enterprise Data
- Internal company data (sales, customer interactions, HR records).
- **Used in:** Business intelligence, predictive analytics.

### E. Web Scraping
- Extracting data from websites using automated scripts.
- **Tools:** BeautifulSoup, Scrapy, Selenium.

---

## Choosing the Right Data Collection Method
- **For real-time data?** Use APIs, IoT sensors, or streaming data pipelines.
- **For customer insights?** Use surveys, interviews, or sentiment analysis.
- **For large datasets?** Use web scraping, open data sources, or databases.

---

# Data Preprocessing and its techniques

Data preprocessing is the process of cleaning, transforming, and preparing raw data before feeding it into a machine learning model. It ensures that the data is structured, consistent, and suitable for analysis.

## Data Preprocessing techniques

### 1. Data Cleaning
This step ensures that data is accurate, consistent, and free from errors.

#### a) Handling Missing Values
- **Remove Missing Data** – If a column has too many missing values, it may be dropped.
- **Imputation** – Replace missing values with:
  - Mean, median, or mode for numerical data.
  - Most frequent category for categorical data.
  - Interpolation or forward-fill methods for time-series data.

#### b) Removing Duplicates
- Identify and remove duplicate records that may distort analysis.

#### c) Handling Outliers
- Detect outliers using box plots, Z-score, or IQR (Interquartile Range).
- Remove or transform outliers if they are due to data entry errors.

#### d) Correcting Inconsistent Data
- Standardizing formats (e.g., "USA" vs. "United States" vs. "U.S.").
- Fixing structural errors such as typos or incorrect units (e.g., kg vs. lbs).

### 2. Data Transformation
After cleaning, data needs to be formatted correctly for analysis.

#### a) Data Type Conversion
- Convert numerical values stored as text to the correct numerical format.
- Ensure categorical values are correctly labeled.

#### b) Feature Scaling (Normalization & Standardization)
Feature scaling ensures that numerical data is within a similar range to prevent models from giving more importance to larger values.
- **Normalization (Min-Max Scaling)**: Scales values between 0 and 1.
  \[ X' = \frac{X - X_{min}}{X_{max} - X_{min}} \]
- **Standardization (Z-score Scaling)**: Centers data around a mean of 0 and standard deviation of 1.
  \[ X' = \frac{X - \mu}{\sigma} \]

#### c) Encoding Categorical Variables
- Convert categorical data into numerical values for machine learning models.
- **One-Hot Encoding** – Creates binary columns for each category.
- **Label Encoding** – Assigns a unique number to each category.

#### d) Feature Engineering
- Create new meaningful features from existing data (e.g., extracting "day of the week" from a date column).

### 4. Data Reduction (Dimensionality Reduction)
Reducing dataset size without losing essential information.

#### Techniques:
- **Feature Selection**: Choosing the most important features using statistical tests.
- **Principal Component Analysis (PCA)**: Reduces dimensionality while preserving variance.

### 5. Data Splitting
#### Train-Test Split:
- Split data into training (e.g., 80%) and testing (e.g., 20%) datasets for model evaluation.

#### Cross-Validation:
- Uses multiple training/testing sets to improve model generalization.

### 6. Data Storage and Integration
- Save the preprocessed data in a structured format (SQL databases, CSV files, or cloud storage).
- Ensure data is ready for further analysis and machine learning model training.

## Summary
- **Data preprocessing** ensures data is clean, structured, and ready for analysis.
- **Data cleaning** involves handling missing values, removing duplicates, and fixing errors.
- **Data transformation** includes scaling, encoding categorical variables, and feature engineering.
- **Data reduction** improves efficiency by reducing unnecessary features.
- **Data splitting** prepares the dataset for training and evaluation.

---

## Loss Function

### What is it?
A loss function measures how well a machine learning model performs by quantifying the difference between predicted and actual values.

### Purpose
Guides the model to improve by minimizing the loss during training.

### Common Loss Functions
- **Mean Squared Error (MSE):** Used for regression tasks.
- **Mean Absolute Error (MAE):** Also used for regression.
- **Cross-Entropy Loss:** Used for classification tasks.

---

## Distance Formulas
Distance formulas measure the similarity or difference between data points. They are commonly used in clustering (e.g., K-Means) and nearest-neighbor algorithms.

### Common Distance Metrics
- **Euclidean Distance:** Straight-line distance between two points in space.

---

## Gradient Descent

### What is it?
Gradient Descent is an optimization algorithm used to minimize the loss function (error) in machine learning models.

### How It Works
1. Start with random values for model parameters (e.g., weights in linear regression).
2. Calculate the gradient (derivative) of the loss function with respect to the parameters.
3. Update the parameters in the opposite direction of the gradient to reduce the loss.
4. Repeat until the loss is minimized.

---

## Optimizers
Optimizers are advanced versions of gradient descent that improve convergence and performance.

### Common Optimizers
- **Momentum:**
  - Adds a fraction of the previous update to the current update to speed up convergence.
  - Helps overcome local minima and oscillations.
- **RMSprop:**
  - Adapts the learning rate for each parameter based on the average of recent gradients.
  - Works well for non-stationary problems.
- **Adam (Adaptive Moment Estimation):**
  - Combines Momentum and RMSprop.
  - Adjusts learning rates for each parameter and uses moving averages of gradients.
  - Most commonly used optimizer in practice.


