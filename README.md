# Shopping Trends — Exploratory Data Analysis (EDA)

A Python-based EDA project that explores customer shopping behavior and purchase
patterns using the Shopping Trends dataset.

## 📌 Objective

Analyze shopping trends to uncover insights about customer demographics,
purchase amounts, product categories, and item popularity.

## 📂 Dataset

- **File:** `shopping_trends.csv`
- **Key Columns:** Age, Gender, Item Purchased, Category,
  Purchase Amount (USD), Review Rating

## 🔍 Analysis Covered

- Distribution of Purchase Amounts and Age (Histogram + KDE)
- Outlier detection with Box Plot
- Sales count and average by Gender
- Total sales by Item Purchased
- Sales breakdown by Product Category (Pie Chart)
- Scatter plot: Age vs Purchase Amount by Gender
- Item popularity by order count
- Average Review Rating per Item

## 📊 Libraries Used

| Library       | Purpose                        |
|---------------|--------------------------------|
| pandas        | Data loading & manipulation    |
| numpy         | Numerical operations           |
| matplotlib    | Static charts                  |
| seaborn       | Statistical visualizations     |
| plotly        | Interactive charts             |

## 🚀 How to Run

1. Clone the repository:
```bash
   git clone https://github.com/YOUR_USERNAME/shopping-trends-eda.git
   cd shopping-trends-eda
```

2. Install dependencies:
```bash
   pip install -r requirements.txt
```

3. Place `shopping_trends.csv` in the project folder

4. Open the notebook:
```bash
   jupyter notebook project.ipynb
```

## 📁 Project Structure
