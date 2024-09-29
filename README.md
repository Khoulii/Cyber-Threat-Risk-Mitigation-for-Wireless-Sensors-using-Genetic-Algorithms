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

## Conclusion
The analysis highlights the importance of using advanced algorithms to mitigate cyber threats in wireless sensor networks. By using insights from data analytics, we can better understand the conditions under which attacks are more likely to occur and take preventative measures to protect network integrity.
