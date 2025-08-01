# 🎬 Netflix Data Analysis – Day 1

This project involves **exploratory data analysis (EDA)** on the Netflix Titles dataset using Python in **Google Colab**. It includes steps such as data loading, cleaning, preprocessing, visualization, and insights extraction.

---

## 📦 Dataset Information

- **Source**: [Kaggle - Netflix Titles Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Contents**: Titles, types (Movie/TV Show), cast, country, director, date added, duration, genre, etc.
- **Size**: ~6,000+ rows

---

## 📚 Steps Performed in Day 1

### ✅ Step 1: Import Libraries and Load Dataset
- Imported essential libraries like `pandas`, `numpy`, `matplotlib`, and `seaborn`.
- Loaded the dataset from a CSV file using `pandas`.

### ✅ Step 2: Understand the Dataset
- Displayed top records using `df.head()`.
- Identified columns, datatypes, and null values.
- Question-based analysis with answers to improve data intuition.

### ✅ Step 3: Handling Missing Values
- Dropped nulls in key columns: `date_added`, `rating`, `duration`.
- Replaced nulls in `director`, `cast`, and `country` with `"Unknown"`.

### ✅ Step 4: Feature Engineering
- Converted `date_added` to datetime format.
- Created `year_added` and `month_added` features for deeper time analysis.

### ✅ Step 5: Checking for Duplicates
- Checked for and removed any duplicate records safely.

### ✅ Step 6: Data Type Conversion
- Ensured consistent formatting (e.g., string columns trimmed and standardized).
- Type checking done on `release_year`, `duration`, etc.

### ✅ Step 7: Data Visualization
- Count of Movies vs TV Shows.
- Content added over the years.
- Top genres/categories.
- Country-wise contribution.
- Ratings distribution using bar plots and pie charts.

### ✅ Step 8: Insights and Summary
- Most content is Movies (~70%).
- Majority content was added between 2016–2020.
- USA contributes the largest share of titles.
- "TV-MA", "TV-14", and "R" are the most common ratings.

---

## 📊 Visualizations Used

- `countplot` – Type Distribution
- `lineplot` – Yearly Additions
- `barplot` – Top Categories
- `pie chart` – Ratings Breakdown
- `heatmap` – Null Value Map (Optional)

---

## 🧠 Key Learnings

- Identified trends in content type and release years.
- Cleaned and prepared real-world data.
- Visualized categorical distributions effectively.
- Gained insights into content patterns and popularity.

---

## 💻 Tech Stack

| Tool          | Purpose                  |
|---------------|---------------------------|
| Python        | Core programming          |
| Pandas        | Data manipulation         |
| Matplotlib    | Visualization             |
| Seaborn       | Enhanced visualization    |
| Google Colab  | Notebook environment      |

---

## 🚀 How to Run

1. Clone the repository or download the `.ipynb` file.
2. Open in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook.
3. Make sure to upload the dataset (`netflix_titles.csv`) before running.

---

## 📁 Files

- `netflix_analysis.ipynb`: Notebook with full Day 1 analysis.

---

## 📌 What's Next?

Stay tuned for **Day 2**, where we’ll perform:
- Deeper genre analysis
- Time-series insights
- Correlation and clustering (if applicable)

---

## 🧑‍💻 Author

Raj Jaiswar  
Frontend Dev → Data Science Journey 🚀

---

