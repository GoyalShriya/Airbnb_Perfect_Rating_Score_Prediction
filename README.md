# Airbnb_Perfect_Rating_Score_Prediction
This project develops a predictive model to determine whether an Airbnb listing receives a perfect rating. By integrating host, listing, and review data with local crime metrics and topic modeling of guest feedback, it identifies key drivers of satisfaction, trust, and pricing potential, offering insights to optimize listing performance.

![Python](https://img.shields.io/badge/Language-Python-blue?logo=python\&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/ML-Scikit--Learn-yellow?logo=scikit-learn\&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-Topic%20Modeling-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

### Overview

This project develops a **predictive model** to determine whether an Airbnb listing earns a perfect rating. By integrating host, listing, and review data with external crime statistics and topic modeling of guest reviews, it identifies the **key factors driving satisfaction, trust, and pricing potential**, offering actionable insights for hosts and platform optimization.

---

### Project Scope

* **Objective:** Predict the likelihood of a listing achieving a five-star rating.
* **Data Sources:** Airbnb listings, host and review metadata, and state-level crime statistics.
* **Approach:** Combine structured data with NLP-based sentiment and topic modeling to quantify guest perceptions and property attributes.

---

### Tools & Techniques

| Category                | Tools / Methods                            |
| ----------------------- | ------------------------------------------ |
| **Programming**         | Python, Pandas, NumPy                      |
| **Modeling**            | Scikit-Learn, XGBoost, Logistic Regression |
| **NLP**                 | Topic Modeling (LDA), TF-IDF Vectorization |
| **Visualization**       | Matplotlib, Seaborn                        |
| **Feature Engineering** | Text cleaning, Encoding, Feature scaling   |

---

### Key Insights

* **Best Model:** XGBoost achieved **78% accuracy**, **48% TPR**, and **10% FPR**, demonstrating strong generalization.
* **Top Predictors:** Host responsiveness, early reviews, instant booking, host tenure, and cleanliness terms in guest feedback.
* **Behavioral Insights:** Listings with **experienced hosts**, **free amenities**, and **positive sentiment** in reviews were most likely to earn perfect ratings.
* **Geospatial Trends:** Integrating **crime data** enhanced model accuracy, highlighting how perceived safety influences guest satisfaction.

---

### 💡 Recommendations

* Encourage hosts to maintain **quick communication** and **instant booking availability**.
* Highlight cleanliness and safety in listing descriptions.
* Use **data-driven pricing** aligned with neighborhood reputation and amenities.
* Expand analysis with **temporal trends** (seasonality, review freshness).

---

### Results Summary

* Built a **comprehensive feature set of 85 variables** combining numeric, categorical, and text-based attributes.
* Delivered **explainable predictions** revealing key levers of host success.
* Created visual dashboards to help hosts and Airbnb optimize listings for better guest outcomes.

---

### Author

**Shriya Goyal**
M.S. Business Analytics, University of Maryland

