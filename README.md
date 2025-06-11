🏨 Hotel Booking Cancellation Prediction – INN Hotels Group
📘 Project Overview
With the rise of online booking platforms, hotels face an increasing rate of booking cancellations and no-shows, especially at the last minute. While flexible cancellation policies are customer-friendly, they can be highly detrimental to hotel revenue, logistics, and operations.

INN Hotels Group, a hotel chain based in Portugal, approached us to build a predictive model that could help identify potential cancellations in advance and implement proactive strategies to reduce associated losses.

🎯 Objective
Analyze booking data to identify key factors influencing cancellations.

Build a machine learning model to predict which bookings are likely to be canceled.

Recommend strategies to mitigate revenue loss and optimize resource allocation.

🗃️ Dataset Description
The dataset includes booking details with the following key columns:

Booking_ID: Unique identifier for each booking

no_of_adults, no_of_children, no_of_weekend_nights, type_of_meal_plan

required_car_parking_space, room_type_reserved, lead_time, arrival_date, etc.

booking_status: Target variable (Canceled or Not_Canceled)

🔍 Exploratory Data Analysis
The notebook includes comprehensive EDA to understand:

Trends in cancellations by month and lead time

Impact of meal plan, car parking, and room type on cancellations

Distributions of continuous variables like lead_time and average_price_per_room

🧠 Machine Learning Workflow
Preprocessing: Handling missing values, encoding categorical features

Modeling:

Logistic Regression

Decision Tree

Random Forest

Gradient Boosting

Evaluation:

Accuracy, Precision, Recall, F1-score

Confusion matrix

ROC-AUC analysis

⚙️ Tools & Technologies
Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Imbalanced-learn (for handling class imbalance)

📈 Key Findings
Longer lead times and absence of car parking space requests increased cancellation likelihood.

Bookings with special requests and families with children were less likely to be canceled.

Ensemble models (Random Forest, Gradient Boosting) outperformed simpler models in accuracy and F1-score.

💡 Business Recommendations
Implement dynamic pricing and overbooking strategies based on predicted cancellation risk.

Offer targeted incentives (e.g., non-refundable discounts) to reduce cancellations for high-risk bookings.

Optimize staff scheduling and resource planning using model predictions.
