# 🍽️ Zomato Data Analysis using Python

An exploratory data analysis (EDA) project focused on understanding restaurant trends, customer preferences, ratings, and online ordering patterns using Python.

## 📌 Project Overview

This project explores restaurant data from Zomato to identify patterns in restaurant types, customer engagement, ratings, pricing, and service availability. Using Python libraries for data analysis and visualization, the project transforms raw data into meaningful insights through charts and exploratory analysis.

## 🎯 Objectives

- Analyze the distribution of different restaurant types.
- Explore online ordering and table booking availability.
- Understand restaurant rating patterns.
- Examine customer engagement using vote counts.
- Investigate approximate restaurant costs for two people.
- Present findings through clear and informative visualizations.

## 🛠️ Tech Stack

- **Programming Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Development Environment:** Google Colab, Jupyter Notebook
- **Version Control:** Git, GitHub

## 📊 Dataset Description

The dataset contains **148 restaurant records and 7 columns**.

| Column | Description |
|---|---|
| `name` | Restaurant name |
| `online_order` | Online ordering availability |
| `book_table` | Table booking availability |
| `rate` | Restaurant rating |
| `votes` | Number of customer votes |
| `approx_cost(for two people)` | Approximate cost for two people |
| `listed_in(type)` | Restaurant category |

**Dataset source:** [Public Zomato dataset on GitHub](https://github.com/Shreyagupta-31/Zomato-Data-Analysis)

*Note: The original local dataset file was unavailable, so a publicly available replacement dataset with the expected structure was used to rerun the analysis.*

## 🔍 Project Workflow

1. **Data Loading** — Imported the dataset into Python using Pandas.
2. **Data Inspection** — Examined dataset dimensions, column names, data types, and missing values.
3. **Exploratory Data Analysis** — Investigated restaurant categories, ratings, votes, pricing, and service availability.
4. **Data Visualization** — Used Matplotlib and Seaborn to create charts that make patterns easier to understand.
5. **Insight Exploration** — Examined relationships between restaurant characteristics and customer preferences.

## 📊 Key Findings

Analysis of the 148 restaurant records revealed the following patterns:

- **Restaurant Category:** Dining is the most common category, with 110 restaurants (74.3%), followed by Cafes (23), other (8), and Buffet (7).
- **Customer Engagement:** Empire Restaurant received the highest number of customer votes among the restaurants in the dataset.
- **Restaurant Ratings:** The average rating is **3.63**, while the median rating is **3.7**.
- **Online Ordering:** Restaurants that offer online ordering have an average rating of **3.86**, compared with **3.49** for restaurants without online ordering.
- **Table Booking:** Only 8 restaurants offer table booking, while 140 do not.
- **Cost for Two:** The most frequently listed approximate cost is **₹300**, appearing 23 times.
- **Online Ordering by Category:** Online ordering is more common among Cafes (15 of 23) than Dining restaurants (33 of 110) in this dataset.

### 💡 Conclusion

The analysis shows that Dining restaurants dominate the dataset, while online ordering availability varies by restaurant category. Restaurants offering online ordering also have higher average ratings in this sample, although this relationship does not establish causation. Table booking is relatively uncommon among the restaurants analyzed.

*These findings are based on the 148-record public replacement dataset used to rerun the notebook.*


The notebook contains the analysis code, charts, and outputs used to explore these areas.

## 📂 Project Structure

```text
Zomato-Data-Analysis/
│
├── README.md
└── Zomato_Analysis.ipynb
```

## 🚀 How to Run the Project

1. Open the notebook: [`Zomato_Analysis.ipynb`](./Zomato_Analysis.ipynb).
2. Open it in Google Colab or Jupyter Notebook.
3. Run the code cells in sequence.
4. Review the generated charts and analysis outputs.

The notebook loads the dataset directly from its public GitHub URL, so a separate local CSV file is not required.

## 💡 Skills Demonstrated

- Python programming
- Data inspection and validation
- Exploratory data analysis (EDA)
- Data manipulation with Pandas and NumPy
- Data visualization with Matplotlib and Seaborn
- Interpreting data patterns
- Documenting and publishing projects on GitHub

## 👩‍💻 Author

**Harika**

B.Tech Graduate | Aspiring Data Analyst

[GitHub Profile](https://github.com/Harika25-28)
