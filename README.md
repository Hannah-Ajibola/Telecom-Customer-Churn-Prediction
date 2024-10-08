# Telco Customer Churn Attrition Prediction

Predicting customer churn in the telecommunications industry is crucial for companies to retain customers and improve overall profitability. This repository contains a predictive model for identifying customers at risk of churn, along with tools and resources for analyzing churn patterns and implementing strategies to mitigate customer attrition. Watch the YouTube video below for a quick overview:

| ![Overview](https://github.com/Hannah-Ajibola/Telecom-Customer-Churn-Prediction/blob/cf48559ced3f5daa0bf7417966d2153219b0f9ed/assets/overview.jpg)

---

## Table of Contents
- [Problem Statement](#problem-statement)
- [Objective](#objective)
- [Methodology](#methodology)
- [Data Insights](#data-insights)
- [Power BI Visuals](#power-bi-visuals)
- [Key Findings](#key-findings)
- [References](#references)
- [Usage Instructions](#usage-instructions)
- [Running the Project](#Running-the-Project)
- [Deployment Steps](#Deployment-Steps)

---

## Problem Statement

In the dynamic landscape of the telecommunications industry, customers wield the power to choose from a plethora of service providers for their communication and internet needs. Customer satisfaction plays a pivotal role as users often form opinions about an entire company based on a single interaction. The ubiquitous nature of communication services, intertwined with our daily lives, underscores the significance of understanding and mitigating customer churn.

Churn rate, a key metric representing the number of customers who terminate or do not renew their subscriptions, directly impacts revenue. Given the high costs associated with acquiring new customers, an in-depth churn analysis is imperative. Insights derived from this analysis empower companies to formulate strategic approaches, target specific segments, enhance service quality, and ultimately foster trust with their customers. Building predictive models and generating comprehensive reports through churn analysis thus becomes instrumental in driving sustainable growth.

---

## Objective

The primary objective is to develop a robust predictive model capable of classifying potential churn customers based on a comprehensive set of numerical and categorical features. This poses a binary classification challenge, considering the inherent imbalance in the dataset.

1. **Dataset Overview and Attributes:**
   Providing an in-depth look into the dataset, detailing various attributes such as customerID, gender, SeniorCitizen status, partnership, dependents, tenure, phone services, and more.

2. **Customer Profile Details:**
   Highlighting key customer-related information, covering aspects like demographics, service usage, contract terms, billing preferences, and payment methods.

3. **Internet and Service Features:**
   Elaborating on the availability of internet services and specific features such as online security, backup, device protection, tech support, streaming TV, and streaming movies.

4. **Contract and Billing Information:**
   Describing the terms of customer contracts, paperless billing preferences, payment methods employed, and the associated monthly and total charges.

5. **Churn Status and Analytics Process:**
   Delving into the critical aspect of customer churn, outlining the notebook's contents, which include Dataset Information, Exploratory Data Analysis (EDA), Summary of EDA, Feature Engineering, Modeling, and a Conclusion.

6. **Utilize Power BI for Visual Insights:**
   Implementing Power BI to create interactive visualizations and dashboards that provide deep insights into churn patterns, customer segments, and predictive model performance. This includes visual representations of churn trends, customer demographics, and service usage patterns to facilitate strategic decision-making.


---

## Methodology

1. **Data Collection and Preparation:**
   - Curated a comprehensive dataset comprising customer demographics, service usage details, contract specifics, and billing preferences.
   - Employed rigorous data cleaning and preprocessing techniques to ensure data integrity and consistency.

2. **Exploratory Data Analysis (EDA):**
   - Conducted in-depth EDA to uncover hidden patterns, correlations, and anomalies within the dataset.
   - Visualized key metrics such as customer segmentation by contract type and churn propensity across different customer segments using tools like Power BI for interactive visualizations.

3. **Predictive Modeling:**
   - Developed and fine-tuned machine learning models including Logistic Regression, Random Forest, and Gradient Boosting.
   - Evaluated model performance based on metrics such as accuracy, precision, recall, and ROC-AUC score to select the optimal model for churn prediction.

4. **Power BI for Visual Insights:**
   - Implemented Power BI to create interactive dashboards and visualizations that provide intuitive insights into churn patterns.
   - Visualized model predictions, feature importance, and customer segmentation to facilitate strategic decision-making and operational planning.
---

## Data Insights


Explore profound insights and analytics gleaned from our extensive dataset. Uncover a deeper understanding of customer behaviors, patterns in service usage, and the pivotal factors that influence churn dynamics.


| Feature                                      | Visualization                                                                                       |
|----------------------------------------------|-----------------------------------------------------------------------------------------------------|
| Categorical Features                         | ![Categorical Features](https://github.com/Hannah-Ajibola/Telecom-Customer-Churn-Prediction/blob/c54b16b32f1baa0621c2f0e3f6401316e299f6b5/assets/catg_features.png)   |
| Churn Target Variable                        | ![Churn Target Variable](https://github.com/Hannah-Ajibola/Telecom-Customer-Churn-Prediction/blob/cf48559ced3f5daa0bf7417966d2153219b0f9ed/assets/churn_target_variable.png)  |
| Customer Information                         | ![Customer Information](https://github.com/Hannah-Ajibola/Telecom-Customer-Churn-Prediction/blob/cf48559ced3f5daa0bf7417966d2153219b0f9ed/assets/cust_info.png)   |
| Distribution Analysis                        | ![Distribution Analysis](https://github.com/Hannah-Ajibola/Telecom-Customer-Churn-Prediction/blob/cf48559ced3f5daa0bf7417966d2153219b0f9ed/assets/distbn.png)   |
| Mean Tenure                                  | ![Mean Tenure](https://github.com/Hannah-Ajibola/Telecom-Customer-Churn-Prediction/blob/cf48559ced3f5daa0bf7417966d2153219b0f9ed/assets/mean_tenure.png)         |
|


---

## Power BI Visuals

Explore interactive Power BI visualizations designed to enhance data exploration and decision-making. Visualize customer churn trends, contract preferences, and revenue impact through intuitive and actionable dashboards.

| Overview and Key Metrics | Attrition Insights |
|---------------|-------------|
| ![Overview](https://github.com/Hannah-Ajibola/Telecom-Customer-Churn-Prediction/blob/cf48559ced3f5daa0bf7417966d2153219b0f9ed/assets/overview.jpg) | ![detailed_insights](https://github.com/Hannah-Ajibola/Telecom-Customer-Churn-Prediction/blob/cf48559ced3f5daa0bf7417966d2153219b0f9ed/assets/detailed_insights.jpg) |
| Gain a high-level view of customer churn trends, contract preferences, and revenue impact. This interactive dashboard provides insights into overall churn metrics and key business indicators. | Explore detailed analytics on customer segments, service usage patterns, and churn predictors. This visualization offers a deeper dive into specific data points and trends influencing churn decisions. |






<p align="center">
  <a href="https://app.powerbi.com/links/t0l3Kk1rqd?ctid=a2e8c89e-7534-4ccf-b1fa-00c12005cb9d&pbi_source=linkShare">
    <img src="https://img.shields.io/badge/Power%20BI-Live%20Dashboard-gold?style=for-the-badge&logo=powerbi" alt="Power BI Dashboard">
  </a>
</p>


*Explore the live Power BI dashboard for real-time insights, dynamic data visualization, and comprehensive analytics. Gain actionable intelligence to drive informed decision-making and optimize business performance.*

---

## Key Findings

### Strategic Insights

- **Customer Segmentation:** Identify high-risk customer segments prone to churn.
- **Service Optimization:** Evaluate the impact of service features and contract terms on customer retention.
- **Financial Impact:** Quantify revenue loss due to churn and explore strategies for revenue recovery.


---

## References

- [Average Customer Acquisition Cost by Industry](https://hockeystack.com/blog/average-customer-acquisition-cost-by-industry/)
- [Subscriber Acquisition Cost Examples](https://www.klipfolio.com/resources/kpi-examples/call-center/subscriber-acquisition-cost)
- [Understanding Customer Churn Rate](https://www.zendesk.com/in/blog/customer-churn-rate/#georedirect)
- [Churn Prevention Strategies](https://www.profitwell.com/customer-churn/churn-prevention)

---

## Usage Instructions

### Getting Started

- **Clone the Repository**

  ```` 
   git clone https://github.com/Hannah-Ajibola/Telecom-Customer-Churn-Prediction.git
   cd Telecom-Customer-Churn-Prediction
   ````

- Install the project dependencies by running the following command

   ```
   pip install -r requirements.txt
   ```

- Navigate through the project's directories and files to get acquainted with its structure.


- **Dataset Handling:**

   - Load the dataset using Python, R, or your preferred data analysis tool.
   - Explore and preprocess data to prepare for churn prediction modeling.

- **Model Development:**

   - Train and evaluate machine learning models to predict customer churn.
   - Fine-tune models based on performance metrics to optimize predictions.

---

## Running the Project

- **Start the Application:** Execute the following command to run the project.

   ```bash
   python app.py
   ```

**After you have successfully installed and launched the project, you can utilize it to forecast customer churn. Follow these steps to begin:**

- **Access the Web Interface:** Open your web browser and navigate to:

   ```
   http://127.0.0.1:5000/
   ```

**Upon accessing the interface, you'll encounter a user-friendly web application. Take time to familiarize yourself with its features and explore the various options available for predicting outcomes.**

- **Input Customer Data:** Refer to the on-screen instructions for guidance on entering customer data into the system. Once entered, explore the prediction feature to forecast churn outcomes based on the data provided.
  
- **Analyze Results:** Review the prediction outcomes to gather insights and formulate strategies, such as designing targeted promotions, and effectively applying the project to specific scenarios, such as implementing enticing customer offers.
  
---

## Deployment Steps

- **Select a Hosting Service:** Choose a reputable hosting platform such as Heroku, AWS, Azure, or PythonAnywhere.

- **Create an Account:** Register an account on your chosen hosting platform if you haven't already.

- **Prepare for Deployment:** Ensure your project complies with the hosting service's requirements, including configuration files and dependencies.

- **Deploy Your Project:** Utilize the deployment tools or instructions provided by the hosting platform to launch your project.

- **Access Your Deployed Application:** Visit the URL provided by the hosting platform to interact with your deployed application.

For comprehensive deployment guidelines tailored to your selected hosting service, consult their official documentation. Experience the deployed [version](https://coral-maurita-35.tiiny.site) of the Telecom Churn Prediction project!


### Dataset Usage:

1. Load the dataset using your preferred programming environment (e.g., Python with Pandas).
2. Explore and analyze the dataset attributes and patterns.
3. Utilize the dataset for Telco Customer Churn Classification analysis.

Feel free to adapt the above steps based on your specific use case and programming environment.

---


