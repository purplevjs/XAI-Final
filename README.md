# XAI-Final

1. Research Question
My project is asking this question: Can XAI help detect financial scams better? Financial
scams are becoming more complicated, and it’s important to not only detect them but also
understand why an AI model flags something as suspicious. This project will explore how
making AI more understandable can help financial institutions find fraud while reducing
mistakes.


2. Why This Topic Matters
Financial scams cost people and companies a lot of money each year. AI is already used to
detect these scams, but the problem is that AI models are often “black boxes” where we
don’t know why they made a decision. This is risky because it can lead to ignoring actual
fraud or flagging legitimate transactions. If AI models were more explainable, professionals
could understand why a transaction was flagged, which would make the process more
reliable. Personally, this topic is important to me because it mixes two interests: fighting
financial fraud and working with AI. Making AI systems more transparent can help prevent
more scams and build trust in these tools.


3. Data Sources
Source: UCI Repository - Default of Credit Card Clients Dataset
Key Features:
LIMIT_BAL: Credit limit.
PAY_X: Payment status for months X.
BILL_AMT_X: Bill statement amounts for months X.
PAY_AMT_X: Payment amounts for months X.
AGE: Age of the client.
Target Variable:
default_payment_next_month:
0 = No default, 1 = Default.



4. Tools and Libraries Used:
Python Libraries:
pandas for data preprocessing.
sklearn for model building and evaluation.
shap for global and local feature explanations.
lime for case-by-case predictions.
matplotlib for visualizations.
Machine Learning Model: Random Forest Classifier.



5. Future Work
- Apply the methodology to larger, real-world datasets.
- Experiment with other XAI tools like Anchors or Integrated Gradients.
- Explore model optimization techniques for better accuracy and speed.
