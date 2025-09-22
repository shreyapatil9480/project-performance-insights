
# Project Performance Insights

This repository contains a synthetic dataset and analytical notebook designed to showcase skills relevant to business analysis, program management, and data analysis roles. The project simulates 200 projects with various performance metrics and demonstrates how to extract insights through exploratory analysis and predictive modelling.

## Dataset

The **synthetic_project_data.csv** file includes the following columns:

| Column | Description |
| ------ | ----------- |
| `project_id` | Unique identifier for each project |
| `project_name` | Name of the project |
| `start_date` | Project start date |
| `end_date` | Project end date |
| `planned_duration_days` | Planned duration of the project in days |
| `actual_duration_days` | Actual duration of the project in days |
| `budget` | Planned budget for the project (USD) |
| `actual_cost` | Actual cost incurred (USD) |
| `team_size` | Number of team members |
| `complexity_score` | Project complexity on a scale of 1–10 |
| `risk_level` | Categorical risk level: Low, Medium, or High |
| `customer_satisfaction` | Simulated customer satisfaction score (0–100) |
| `cost_overrun_pct` | Percentage over or under budget |
| `success` | Binary indicator of project success (1 if within 10% of budget and schedule with no high risk, 0 otherwise) |

## Notebook

The **analysis.ipynb** notebook walks through the following steps:

1. **Data loading and inspection** – Reads the dataset and displays basic statistics.
2. **Exploratory Data Analysis (EDA)** – Visualizes distributions, relationships, and correlations among variables.
3. **Classification Model** – Uses logistic regression to classify whether a project is successful based on budget, planned duration, team size, complexity, and risk level.
4. **Regression Model** – Uses a Random Forest regressor to predict customer satisfaction from project attributes and cost overruns.
5. **Conclusions** – Summarizes key insights and modelling results.

All plots are generated using Matplotlib and Seaborn. Machine learning models are built with scikit-learn.

## Getting Started

To run the notebook locally:

```bash
# Clone the repository
https://github.com/shreyapatil9480/project-performance-insights.git

# Navigate to the project directory
cd project-performance-insights

# Create a virtual environment (optional) and install dependencies
python -m venv venv
source venv/bin/activate  # On Windows use venv\Scriptsctivate
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook
```

Open `analysis.ipynb` in your browser to explore the analysis.

## License

This project is released for demonstration purposes and does not contain any real or proprietary data.
