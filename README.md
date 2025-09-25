# 📊 Demographic Data Analyzer

This project contains a Python script that uses the **pandas** library to perform various calculations and derive insights from a public demographic dataset (typically the US Adult Census data, found in `adult.data.csv`).

The primary goal of this script is to answer several key questions about the data, including statistics on race, education, work hours, and income ($>50K$).

---

## 🚀 Metrics Calculated

The `calculate_demographic_data` function processes the dataset and returns the following key demographic statistics:

1.  **Race Count**: The number of individuals representing each race in the dataset.

2.  **Average Age of Men**: The average age of male participants, rounded to one decimal place.

3.  **Percentage with Bachelors**: The percentage of the population holding a Bachelor's degree.

4.  **High/Low Education & Income**:
    * Percentage of people with **advanced education** (`Bachelors`, `Masters`, or `Doctorate`) who earn $>50K$.
    * Percentage of people **without advanced education** who earn $>50K$.

5.  **Minimum Work Hours**: The minimum number of hours worked per week.

6.  **Rich Percentage (Min Workers)**: The percentage of those who work the minimum number of hours per week that earn $>50K$.

7.  **Highest Earning Country**: The country with the highest percentage of people earning $>50K$, and that percentage value.

8.  **Top India Occupation**: The most popular occupation among individuals in India who earn $>50K$.

---

## 🛠️ Prerequisites

To run this script, you need:

* **Python 3**
* **Pandas Library**: A powerful library for data analysis.

You can install the necessary library using pip:

```bash
pip install pandas
