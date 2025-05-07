
# 🏥 Healthcare Appointment No-Show Prediction

## 📌 Overview
This project aims to predict whether patients will miss their medical appointments using historical healthcare data. Missed appointments result in underutilized resources and increased healthcare costs. By leveraging machine learning, we can proactively manage scheduling and improve patient outcomes.

---

## 🎯 Objective
- Predict the likelihood of appointment no-shows.
- Analyze contributing factors such as age, SMS reminders, and appointment timing.
- Provide recommendations to optimize scheduling and reduce missed appointments.

---

## 🛠️ Tools Used
- **Python**: Data preprocessing, feature engineering, model training.
- **Scikit-learn**: Machine learning (Decision Tree classifier).
- **Pandas**: Data manipulation and cleaning.
- **Power BI**: Interactive dashboards for trend analysis and stakeholder communication.
- **Jupyter Notebook**: Development and testing environment.

---

## 📂 Project Structure
```
healthcare-no-show/
│
├── data/                          # Raw and cleaned appointment datasets
├── notebooks/                     # Jupyter Notebooks (model training, analysis)
│   └── healthcare_appointment.ipynb
├── dashboards/                    # Power BI Dashboard (.pbix)
├── reports/                       # Summary report (PDF, PPT)
│   └── Healthcare_No_Show_Prediction_Report.pdf
├── README.md                      # Project documentation
```

---

## 📊 Power BI Dashboard
The Power BI dashboard visualizes:
- No-show distribution by age, gender, and neighborhood.
- Impact of SMS reminders.
- Trends by weekday and booking lead time.

📁 Power BI File: `dashboards/No_Show_Analysis_Dashboard.pbix`

---

## 🧠 Model Insights
- **Model Type**: Decision Tree Classifier.
- **Key Predictors**: Age, Days Since Booking, SMS Reminder Received, Appointment Weekday.
- **Performance Metrics**: Accuracy, Precision, Recall.

---

## ✅ Recommendations
- Send SMS reminders closer to the appointment date.
- Follow up with high-risk groups (e.g., younger adults, early-week appointments).
- Consider double-booking strategies during peak no-show slots.

---

## 📧 Contact
For queries or feedback, contact: `your.email@example.com`
