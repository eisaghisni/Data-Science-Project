# 🏨 Hotel Booking Cancellations – Data Science Project

## Project Description

This project focuses on analyzing and modeling hotel booking cancellations using data science methods. By leveraging a publicly available dataset from Kaggle, we explored the data, performed preprocessing, and developed predictive models to identify key factors that influence booking cancellations.

Cancellations can significantly impact hotel revenue and operational efficiency. Therefore, understanding customer behaviors behind cancellations helps management develop smarter strategies in promotions, refund policies, and reservation systems.
## Objectives

- Identify the most influential features contributing to booking cancellations.
- Develop a predictive model to classify potential cancellations.
- Provide actionable insights for hotel management.
## Dataset

- **Source**: Kaggle – Hotel Booking Demand Dataset  
- **Total Records**: 119,390 rows  
- **Key Features**:
  - `hotel`, `is_canceled`, `lead_time`, `market_segment`
  - `is_repeated_guest`, `previous_cancellations`, `reserved_room_type`
  - `deposit_type`, `adr`, `booking_changes`, `reservation_status_date`
## Project Workflow

1. **Exploratory Data Analysis (EDA)**  
   - Cancellation distribution  
   - Feature correlations  
   - Key pattern discovery (e.g., lead time, pricing, booking behavior)

2. **Data Preprocessing**  
   - Categorical encoding (LabelEncoder)  
   - Handling missing values  
   - Normalization using MinMaxScaler  
   - Outlier handling  
   - Data balancing due to class imbalance

3. **Modeling**  
   - Various classification models tested  
   - Best performance model: [insert model name from notebook]  
   - Evaluation: Accuracy, Precision, Recall, F1-Score
## Key Insights

- Guests who book far in advance, are not repeat customers, and don’t make deposits are more likely to cancel.
- The most influential features: `lead_time`, `adr`, and `previous_cancellations`.
- The best predictive model achieved [XX%] accuracy and can be used for early warning systems.
## Project Team

- M Agil Mubarok (2012210012)  
- Afica Marsha Nurcahaya (2012310002)  
- Ferindriakarina Lintang Helsadamara (2012310007)  
- Eis Aghisni (2012310701)
