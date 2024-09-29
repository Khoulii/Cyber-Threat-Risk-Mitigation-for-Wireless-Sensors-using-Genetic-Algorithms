# Cyber Threat Risk Mitigation for Wireless Sensors Using Genetic Algorithms

## Overview
This project investigates various network attacks and their impacts on system performance, focusing on energy consumption and response time in Wireless Sensor Networks (WSNs). By utilizing Genetic Algorithms, the project aims to mitigate cyber threats that degrade network performance.

### Purpose
The primary objective is to study different types of network attacks and their effects on system performance. The study provides insights into energy consumption, response time, and system reliability under the influence of attacks like **Blackhole**, **Flooding**, and **Selective Forwarding**.

## Dataset
The dataset used in this project is derived from the paper *"WSN-BFSF: A New Dataset for Attacks Detection in Wireless Sensor Networks"*. The dataset, obtained from network traffic simulations, has undergone necessary preprocessing to be suitable for analysis using learning models.

### Key Features of the Dataset:
- **Types of Attacks:** Blackhole, Flooding, Selective Forwarding
- **System Events:** Receiving, Dropping, Forwarding
- **Node IDs:** Identification of nodes targeted by attacks
- **Destination Node Count:** Impact of destination node counts on the likelihood of attacks

## Exploratory Data Analysis (EDA)

### Feature Analysis

#### 1. Attack Type Distribution
- **Observation:** Approximately 85% of the dataset indicates no attack. Flooding attacks make up 10% of the data.

<p align="center">
  <img src="https://github.com/user-attachments/assets/a6797e1b-c6e9-4101-9b5c-5fbc7611685d" width="400">
</p>

#### 2. Attack Event Distribution (Blackhole Attacks)
- **Observation:** 80% of the Blackhole attacks occurred during the receiving event, while 20% involved packet drops.

<p align="center">
  <img src="https://github.com/user-attachments/assets/972bdf60-07fe-40e3-8381-84a9ff31cb59" width="400">
</p>

#### 3. Node ID Analysis
- **Observation:** A comparative analysis of nodes targeted by Blackhole attacks versus other attack types.

<p align="center">
  <img src="https://github.com/user-attachments/assets/dc65d115-b89a-4252-b67b-a00cb5a6ffa7" width="400">
</p>

#### 4. Destination Node Count
- **Observation:** Flooding attacks occurred 94% of the time when the destination node number was between 36 and 40.

<p align="center">
  <img src="https://github.com/user-attachments/assets/0abc542c-c17f-496b-b3c8-9f61904897a6" width="400">
  <img src="https://github.com/user-attachments/assets/e59c75ce-76c7-4864-b85c-ff16fb358ba0" width="400">
</p>

### Insights and Findings
The analysis of this dataset is critical in making informed decisions about network security. By identifying attack patterns, particularly Flooding Attacks, we can proactively strengthen security measures.

#### Key Finding: Flooding Attack Patterns
- Flooding Attacks are more likely to occur when:
  - **Hop count:** Between 3 and 7
  - **TTL:** Between 24 and 28
  - **Time:** Between 65 and 100
  
In these conditions, Flooding Attacks make up 62% of the data, while the remaining 32% reflects normal network behavior. 

#### Business Impact
- **Actionable Insight:** These findings can help businesses enhance network security by identifying high-risk periods and parameters. For example, organizations can implement targeted defenses or real-time monitoring based on the identified patterns.
  
<p align="center">
  <img src="https://github.com/user-attachments/assets/fb7de93a-5b85-41b6-b17b-484d364c7958" width="400">
  <img src="https://github.com/user-attachments/assets/5c42eb3a-e691-4ea4-8daf-7d6331ef3102" width="400">
  <img src="https://github.com/user-attachments/assets/2ba0be4d-9425-4de9-b5f3-61c0eb745993" width="400">
</p>

# Cyber Threat Risk Mitigation for Wireless Sensors Using Genetic Algorithms

## Overview
This project investigates various network attacks and their impacts on system performance, focusing on energy consumption and response time in Wireless Sensor Networks (WSNs). By utilizing Genetic Algorithms, the project aims to mitigate cyber threats that degrade network performance.

### Purpose
The primary objective is to study different types of network attacks and their effects on system performance. The study provides insights into energy consumption, response time, and system reliability under the influence of attacks like **Blackhole**, **Flooding**, and **Selective Forwarding**.

## Dataset
The dataset used in this project is derived from the paper *"WSN-BFSF: A New Dataset for Attacks Detection in Wireless Sensor Networks"*. The dataset, obtained from network traffic simulations, has undergone necessary preprocessing to be suitable for analysis using learning models.

### Key Features of the Dataset:
- **Types of Attacks:** Blackhole, Flooding, Selective Forwarding
- **System Events:** Receiving, Dropping, Forwarding
- **Node IDs:** Identification of nodes targeted by attacks
- **Destination Node Count:** Impact of destination node counts on the likelihood of attacks

## Exploratory Data Analysis (EDA)

### Feature Analysis

#### 1. Attack Type Distribution
- **Observation:** Approximately 85% of the dataset indicates no attack. Flooding attacks make up 10% of the data.

<p align="center">
  <img src="https://github.com/user-attachments/assets/a6797e1b-c6e9-4101-9b5c-5fbc7611685d" width="400">
</p>

#### 2. Attack Event Distribution (Blackhole Attacks)
- **Observation:** 80% of the Blackhole attacks occurred during the receiving event, while 20% involved packet drops.

<p align="center">
  <img src="https://github.com/user-attachments/assets/972bdf60-07fe-40e3-8381-84a9ff31cb59" width="400">
</p>

#### 3. Node ID Analysis
- **Observation:** A comparative analysis of nodes targeted by Blackhole attacks versus other attack types.

<p align="center">
  <img src="https://github.com/user-attachments/assets/dc65d115-b89a-4252-b67b-a00cb5a6ffa7" width="400">
</p>

#### 4. Destination Node Count
- **Observation:** Flooding attacks occurred 94% of the time when the destination node number was between 36 and 40.

<p align="center">
  <img src="https://github.com/user-attachments/assets/0abc542c-c17f-496b-b3c8-9f61904897a6" width="400">
  <img src="https://github.com/user-attachments/assets/e59c75ce-76c7-4864-b85c-ff16fb358ba0" width="400">
</p>

### Insights and Findings
The analysis of this dataset is critical in making informed decisions about network security. By identifying attack patterns, particularly Flooding Attacks, we can proactively strengthen security measures.

#### Key Finding: Flooding Attack Patterns
- Flooding Attacks are more likely to occur when:
  - **Hop count:** Between 3 and 7
  - **TTL:** Between 24 and 28
  - **Time:** Between 65 and 100
  
In these conditions, Flooding Attacks make up 62% of the data, while the remaining 32% reflects normal network behavior. 

#### Business Impact
- **Actionable Insight:** These findings can help businesses enhance network security by identifying high-risk periods and parameters. For example, organizations can implement targeted defenses or real-time monitoring based on the identified patterns.
  
<p align="center">
  <img src="https://github.com/user-attachments/assets/fb7de93a-5b85-41b6-b17b-484d364c7958" width="400">
  <img src="https://github.com/user-attachments/assets/5c42eb3a-e691-4ea4-8daf-7d6331ef3102" width="400">
  <img src="https://github.com/user-attachments/assets/2ba0be4d-9425-4de9-b5f3-61c0eb745993" width="400">
</p>

## Predictive Analytics

To predict outcomes based on the dataset, several preprocessing steps were required to prepare the data for machine learning models. Below is a breakdown of key steps involved:

### 1. Dropping Irrelevant Features
I removed the columns Trace_Level, Mac_Type_Pckt, and Des_IP_Port because they are either redundant or irrelevant for predicting the outcome. These features may not contribute meaningful information to the model and could introduce noise, negatively impacting the model's performance. By dropping them, I streamlined the dataset, improving model training speed and accuracy.

### 2. Encoding Categorical Variables
I used one-hot encoding via the pd.get_dummies() function to convert the categorical variables (behaviour, Type, and Event) into numerical format. This step is necessary because most machine learning algorithms require numerical input. The drop_first=True argument was used to avoid multicollinearity by dropping one category from each variable, ensuring that the encoded columns are not linearly dependent on each other.

### 3. Standardizing the Time Feature
I standardized the Time feature using StandardScaler. Standardization rescales the data so that it has a mean of 0 and a standard deviation of 1. This step is essential because Time is measured on a different scale than other features, and machine learning models typically perform better when the features are on similar scales. The standardized Time was then added back into the dataset as a new feature, Time_standardized.

### 4. Normalizing Numerical Features
I normalized the numerical features using MinMaxScaler, which scales the data between 0 and 1. Normalization is important for algorithms like linear regression and decision trees, as it ensures that no feature dominates others simply because of its scale. The original columns were replaced with their normalized counterparts to make the dataset more suitable for machine learning algorithms.

### 5. Feature Selection
To improve the performance of the machine learning models, I applied two feature selection techniques:
#### - SelectKBest: This method selects the top k features that have the strongest relationship with the target variable based on statistical tests.
#### - SelectFromModel: This technique selects important features based on a machine learning model, such as Random Forest, which provides a ranking of feature importance.
Feature selection helps in reducing overfitting, improving accuracy, and speeding up the training process by focusing only on the most relevant variables.
The SelectKBest showed moderate effectiveness in Linear Regression but performed excellently with Decision Tree and Random Forest models, whereas the SelectFromModel showcased near-perfect performance with Decision Tree and Random Forest but failed in Linear Regression.

### 6. Predictive Model Results
I employed several predictive models to analyze the dataset:
- Linear Regression:
R² (SelectKBest): 0.618 (Moderate performance)
R² (SelectFromModel): 0.0078 (Poor performance)

- Decision Tree:
R² (SelectKBest): 1.0 (Perfect fit)
R² (SelectFromModel): Also performs exceptionally well.

- Random Forest:
R² (SelectKBest): 0.9999999354 (Almost perfect)
R² (SelectFromModel): Also performs exceptionally well.

### Evaluation
- Effectiveness: Decision Tree and Random Forest models performed exceptionally well with near-zero error. Linear Regression was less effective, especially with SelectFromModel.
- Limitations: Linear models assume linear relationships, which may not be sufficient for this dataset. Feature selection techniques can miss feature interactions and struggle with correlated features.
- Potential Improvements: Further exploration of feature engineering or alternative feature selection methods could enhance performance, particularly for Linear Regression.
<p align="center">
  <img src="https://github.com/user-attachments/assets/32a31975-4b47-4192-ac50-9ab37b292363" width="400">
  <img src="https://github.com/user-attachments/assets/1d285d84-1f2e-4d3b-82a9-0514f083400b" width="400">
</p>

## Conclusion
The analysis highlights the importance of using advanced algorithms to mitigate cyber threats in wireless sensor networks. By using insights from data analytics, we can better understand the conditions under which attacks are more likely to occur and take preventative measures to protect network integrity.
