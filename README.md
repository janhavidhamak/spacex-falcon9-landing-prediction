# SpaceX Falcon 9 Landing Prediction

##  Project Overview
Predicting whether the SpaceX Falcon 9 first stage will successfully land
after launch, using machine learning classification models.
This project is part of the **IBM Data Science Professional Certificate** 
on Coursera.

##  Objective
SpaceX advertises Falcon 9 rocket launches at $62 million, significantly 
cheaper than other providers ($165 million+). The cost savings come from 
reusing the first stage. Predicting landing success helps estimate launch costs.

##  Project Structure
```
├── 1_data_collection_api.ipynb
├── 2_data_collection_webscraping.ipynb  
├── 3_data_wrangling.ipynb
├── 4_eda_sql.ipynb
├── 5_eda_visualization.ipynb
├── 6_machine_learning_prediction.ipynb
└── README.md
```

## 🔧Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Folium, Plotly Dash
- Scikit-learn
- SQL

##  ML Models Used
| Model | Accuracy |
|-------|----------|
| Logistic Regression | 83.33% |
| Support Vector Machine | 83.33% |
| Decision Tree | 94.4% |
| K-Nearest Neighbors | 83.34% |

##  Key Findings
- Best performing model: **[Decision Tree ]**
- Overall test accuracy: **94.4%**

## Installation & Usage
```bash
git clone https://github.com/yourusername/spacex-falcon9-landing-prediction
cd spacex-falcon9-landing-prediction
pip install -r requirements.txt
```

##  Certificate
IBM Data Science Professional Certificate — Coursera  

## Lab Authors: Joseph Santarcangelo, Yan Luo, Azim Hirjani, Lakshmi Holla
