# Airline Customer Satisfaction Prediction Using Logistic Regression

## Project Overview

This project analyzes airline passenger survey data using Logistic Regression to predict customer satisfaction. The objective is to identify the factors that most strongly influence passenger satisfaction and provide data-driven recommendations that airlines can use to improve customer experience and retention.

The analysis includes data preprocessing, categorical variable encoding, train-test splitting, logistic regression modeling, model evaluation using Accuracy, Precision, Recall, and Confusion Matrix, coefficient interpretation, and business recommendations.

---

## Project Objectives

* Load and preprocess the airline dataset
* Encode categorical variables for classification modeling
* Split the data into training and testing sets
* Build a Logistic Regression model
* Evaluate model performance using Accuracy, Precision, Recall, and Confusion Matrix
* Interpret model coefficients to identify the drivers of customer satisfaction
* Provide business recommendations based on model findings

---

## Dataset Variables

| Variable                          | Description                         |
| --------------------------------- | ----------------------------------- |
| Gender                            | Passenger gender                    |
| Customer Type                     | Loyal or disloyal customer          |
| Age                               | Passenger age                       |
| Type of Travel                    | Business or personal travel         |
| Class                             | Business, Eco, or Eco Plus          |
| Flight Distance                   | Distance travelled                  |
| Inflight wifi service             | Rating of Wi-Fi service             |
| Departure/Arrival time convenient | Rating of schedule convenience      |
| Ease of Online booking            | Rating of booking experience        |
| Gate location                     | Rating of gate accessibility        |
| Food and drink                    | Rating of food and beverage service |
| Online boarding                   | Rating of online boarding           |
| Seat comfort                      | Rating of seat comfort              |
| Inflight entertainment            | Rating of entertainment quality     |
| On-board service                  | Rating of onboard service           |
| Leg room service                  | Rating of leg room                  |
| Baggage handling                  | Rating of baggage handling          |
| Checkin service                   | Rating of check-in process          |
| Online support                    | Rating of customer support          |
| Arrival Delay in Minutes          | Arrival delay                       |
| satisfaction                      | Target variable                     |

---

## Methodology

The project followed the steps below:

1. Data Loading and Inspection
2. Missing Value Handling
3. Encoding Categorical Variables
4. Feature Selection
5. Train-Test Split
6. Logistic Regression Modeling
7. Model Evaluation
8. Confusion Matrix Analysis
9. Feature Importance Analysis
10. Business Interpretation and Recommendations

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Installation

Install the required libraries using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## Running the Project

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Navigate to the project folder:

```bash
cd Logistic-Regression-Evaluation
```

3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Open:

```text
logistic_regression_analysis.ipynb
```

5. Run all cells sequentially.

---

## Model Performance

| Metric    | Value  |
| --------- | ------ |
| Accuracy  | 0.8274 |
| Precision | 0.8434 |
| Recall    | 0.8429 |

### Confusion Matrix

| Actual / Predicted | Unsatisfied | Satisfied |
| ------------------ | ----------: | --------: |
| Unsatisfied        |        9437 |      2238 |
| Satisfied          |        2246 |     12055 |

---

## Key Findings

* The Logistic Regression model achieved an accuracy of **82.74%**, demonstrating strong classification performance.
* Precision and Recall values above **84%** indicate that the model effectively identifies satisfied customers while maintaining balanced predictions.
* **Inflight Entertainment** was the strongest positive driver of customer satisfaction.
* **On-board Service**, **Seat Comfort**, **Check-in Service**, and **Ease of Online Booking** positively influenced passenger satisfaction.
* **Disloyal Customers** exhibited the strongest negative effect on satisfaction.
* Passengers travelling for **Personal Travel** and those in **Economy** or **Economy Plus** classes were less likely to be satisfied.
* The model revealed that customer experience factors have a substantial impact on passenger satisfaction levels.

---

## Recommendation

Based on the model results, airlines should prioritize improvements in inflight entertainment, onboard service quality, seat comfort, and online booking systems.

The analysis also highlights the importance of strengthening customer loyalty programs, since disloyal customers were associated with the greatest reduction in satisfaction. Additionally, improving the economy-class experience may help increase overall customer satisfaction and retention.

These findings provide actionable insights that can support data-driven decisions aimed at enhancing passenger experience and increasing customer loyalty.

---

## Repository Structure

```text
│morgtech/logistic-regression-evaluation/
├── Invistico_Airline.csv
├── README.md 
├── logistic_regression_analysis.ipynb
└── requirements.txt
```

---

## Author

Godwill Morgan Lekwa
