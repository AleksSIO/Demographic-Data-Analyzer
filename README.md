# 🧑‍💼 Demographic Data Analyzer

This project is part of the [freeCodeCamp Data Analysis with Python](https://www.freecodecamp.org/learn/data-analysis-with-python/) certification.  
It analyzes U.S. Census demographic data to extract statistical insights about education, work hours, income, and more.

---

## 📁 Project Structure

```
demographic_data_analyzer.py   # Script containing the analysis logic  
main.py                        # Entrypoint to test your function  
test_module.py                 # Unit tests to validate your solution  
adult.data.csv                 # Dataset (1994 Census demographic data)  
```

---

## 📊 Features

- Loads and processes demographic data using Pandas  
- Calculates key statistics such as:
  - Number of each race represented
  - Average age of men
  - Percentage of people with a Bachelor's degree
  - Income analysis based on education level
  - Minimum work hours and associated income
  - Country with the highest percentage of high earners
  - Most popular occupation for high earners in India

---

## 🧪 Technologies Used

- **Python 3**
- **Pandas**

---

## 🚀 How to Run the Project

1. Install the required dependency:

```bash
pip install pandas
```

2. Run the script:

```bash
python main.py
```

This will:

- Run your `calculate_demographic_data()` function  
- Print the returned statistics  
- Run unit tests from `test_module.py`

---

## 🧾 Output Example

The function `calculate_demographic_data()` should return a dictionary with keys like:

```python
{
  'race_count': Series,
  'average_age_men': float,
  'percentage_bachelors': float,
  'higher_education_rich': float,
  'lower_education_rich': float,
  'min_work_hours': int,
  'rich_percentage_min_hours': float,
  'highest_earning_country': str,
  'highest_earning_country_percentage': float,
  'top_IN_occupation': str
}
```

Each value should be correctly calculated, rounded where needed, and validated by the unit tests.

---

## 📚 Dataset Source

> 1994 U.S. Census Adult Data  
> Provided by the UCI Machine Learning Repository

