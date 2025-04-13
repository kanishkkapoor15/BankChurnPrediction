# BankChurnPrediction
A deep learning binary classification model to predict Customer Churn in R.
<img width="627" alt="Screenshot 2025-04-13 at 12 13 40 PM" src="https://github.com/user-attachments/assets/4784447a-b50b-4f3f-b915-2080c8ba6e21" />


This project aimed to develop a predictive model to identify potential customer churn in a bank using deep learning techniques. After thorough preprocessing—including handling class imbalance via SMOTE, feature normalization, and one-hot encoding—we trained a neural network using the Keras library in R.
<img width="626" alt="Screenshot 2025-04-13 at 12 19 51 PM" src="https://github.com/user-attachments/assets/7e683f52-22c3-46e4-bdb1-5aa15fb05177" />

<img width="627" alt="Screenshot 2025-04-13 at 11 38 01 AM" src="https://github.com/user-attachments/assets/6ab5575e-5f5f-45b4-881d-f91476093417" />

The final model achieved strong overall accuracy, with high performance in predicting non-churning customers (True Negatives = 1545). However, the model’s recall for churners was moderate, indicating room for improvement in capturing customers who are at actual risk of leaving (False Negatives = 178).
<img width="629" alt="Screenshot 2025-04-13 at 12 16 37 PM" src="https://github.com/user-attachments/assets/f6a30300-2d5c-4a33-8cae-edd08df3f46e" />


Key takeaways:
	•	Accuracy and precision were satisfactory, showing the model performs well under general conditions.
	•	Recall can be enhanced by exploring advanced techniques such as ensemble methods or tuning decision thresholds.
	•	The confusion matrix highlights the need for the bank to focus on reducing false negatives, which represent missed churners and could translate to lost revenue.
 
 <img width="627" alt="Screenshot 2025-04-13 at 12 19 41 PM" src="https://github.com/user-attachments/assets/ac1ec2f2-1b50-4cfd-bc63-c9cdaec4f19b" />


Going forward, integrating additional customer behavior data (e.g., transaction frequency, support tickets, NPS scores) could further improve churn prediction. Overall, this project demonstrates the potential of data-driven approaches in proactively managing customer retention strategies.
