# Cyber-Threat-Risk-Mitigation-for-Wireless-Sensors-using-Genetic-Algorithms
The purpose of this project is to study different types of network attacks and their effects on system performance, particularly in terms of energy consumption and response time.

## The Dataset
The dataset has been extratced from the paper "WSN-BFSF: A New Dataset for Attacks Detection in Wireless Sensor Networks", where it was obtained from a simulation and was made ready to be examined with learning models after the necessary preprocessing.

## Descriptive Analytics (EDA)
I have analyzed the dataset, derived from network traffic simulations, to identify patterns associated with different types of network attacks, such as Blackhole, Flooding, and Selective 
Forwarding, using data analytics tools and techniques to derive actionable insights from raw network traffic data.
#### Feature Analysis
1. Type: Almost 85% of the type is no attack. The flooding shaped most of the attacks with around 10%.
![image](https://github.com/user-attachments/assets/a6797e1b-c6e9-4101-9b5c-5fbc7611685d)
2. Event: Most of the blackhole attacks happened on the receiving event by almost 80%, and the dropping is the second most making around 20% of the attacks.
![image](https://github.com/user-attachments/assets/972bdf60-07fe-40e3-8381-84a9ff31cb59)
3. Node_id: Analyzing the nodes that faced blackhole attacks, in comparison of the other types.
![image](https://github.com/user-attachments/assets/dc65d115-b89a-4252-b67b-a00cb5a6ffa7)
4. Dest_Node_Num: When the Dest_Node_Num is between 36 and 40, the flooding percentage was 94%.
![image](https://github.com/user-attachments/assets/0abc542c-c17f-496b-b3c8-9f61904897a6) ![image](https://github.com/user-attachments/assets/e59c75ce-76c7-4864-b85c-ff16fb358ba0)
#### Finding
The analysis conducted on the dataset plays a pivotal role in shaping effective business decisions by uncovering insights into network security and performance. By identifying patterns associated with different types of attacks, such as Flooding Attacks, the analysis offers a comprehensive understanding of potential vulnerabilities. 
In this context, the findings show that when the hop count is between 3 and 7, TTL is between 24 and 28, and the time falls within the range of 65 to 100, there is a significant occurrence of Flooding Attacks, comprising 62% of cases, while the remaining 32% is considered normal network behaviour.
This information is highly significant as it highlights specific conditions under which Flooding Attacks are more likely to occur. For instance, businesses can utilize these insights to implement targeted security measures during vulnerable time intervals and adjust network parameters to mitigate the risk of such attacks. Additionally, these findings underscore the need to strengthen network defences and proactively monitor for any anomalies that align with the identified patterns.
![image](https://github.com/user-attachments/assets/fb7de93a-5b85-41b6-b17b-484d364c7958)
![image](https://github.com/user-attachments/assets/5c42eb3a-e691-4ea4-8daf-7d6331ef3102)
![image](https://github.com/user-attachments/assets/2ba0be4d-9425-4de9-b5f3-61c0eb745993)






