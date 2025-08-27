
# Project Management Analytics

This project demonstrates a data analytics workflow tailored for roles such as **Business Analyst**, **Program Manager**, and **Data Analyst**. It includes a synthetic dataset representing project management data, exploratory data analysis (EDA), and predictive models.

## Dataset

The dataset (`synthetic_project_data.csv`) contains 1000 records of synthetic projects with the following columns:

- `Project_ID`: Unique identifier for each project.
- `Project_Priority`: Priority of the project (Low, Medium, High).
- `Phase`: Current phase of the project (Planning, Execution, Monitoring, Closure).
- `Team_Size`: Number of team members working on the project.
- `Duration_Months`: Planned duration of the project in months.
- `Budget`: Allocated budget for the project (USD).
- `Expenditure`: Amount spent so far (USD).
- `Risk_Rating`: Risk rating on a scale of 1 to 10.
- `Completion_Percent`: Percentage completion of the project (0-100%).
- `On_Time`: Indicator (1/0) showing whether the project is on schedule.
- `Success`: Indicator (1/0) showing overall success based on budget, schedule, risk, and completion.

## Analysis Notebook

The Jupyter notebook (`analysis.ipynb`) performs the following:

1. **Data Loading & Cleaning**: Reads the dataset and checks for missing values.
2. **Exploratory Data Analysis**:
   - Descriptive statistics.
   - Distribution plots of key numerical variables.
   - Bar charts for categorical variables.
   - Correlation matrix heatmap.
3. **Predictive Modeling**:
   - A logistic regression model to predict project success (`Success`).
   - A random forest classifier for comparison.
   - Evaluation of models using accuracy, precision, recall, and ROC curves.

## Getting Started

To run the analysis locally:

1. Clone this repository.
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:

```bash
jupyter notebook analysis.ipynb
```

## Usage

This project is intended to showcase analytical and programming skills useful for business analytics and project management roles. Feel free to modify the dataset generation or analysis steps to explore different scenarios.

## Additional Notes

This branch demonstrates how to create a pull request by adding a simple section to the README.
