# Developing Intuition

What's happening under the hood? Here's a collection of notebooks that do things the hard way, for the purpose of understand things. 

## From Scratch: Fitting A Linear Regression Model

### Many Models
<img width="570" height="535" alt="Screenshot 2025-09-14 at 7 06 19 PM" src="https://github.com/user-attachments/assets/cac128f5-41e2-483f-8023-e8b21d14e1cf" />

### First Randomly Chosen Model
<img width="916" height="479" alt="Screenshot 2025-09-14 at 7 06 02 PM" src="https://github.com/user-attachments/assets/827227e2-ae52-48f4-ad63-afc65696fc35" />

### Second Randomly Chosen Model
<img width="910" height="491" alt="Screenshot 2025-09-14 at 7 06 10 PM" src="https://github.com/user-attachments/assets/8cc9f66e-4b91-4c89-a3cd-f0298993b2ee" />

### Grid Search
<img width="749" height="454" alt="Screenshot 2025-09-14 at 7 05 46 PM" src="https://github.com/user-attachments/assets/415a47c6-a62b-4456-9d38-cfe53b9078a1" />

### Final Output

Our optimal model using coarse **grid search** has:   intercept: -1.0204, and slope: 36.73 #could be improved

Our optimal model using **Newson-Raphson** has:       intercept: -0.0797, and slope: 36.92

Our optimal model using **sklearn** has:              intercept: -0.0797, and slope: 36.92

<img width="579" height="454" alt="Screenshot 2025-09-14 at 7 09 09 PM" src="https://github.com/user-attachments/assets/1fba7c52-f6b5-4904-8d16-a452d34137ee" />




