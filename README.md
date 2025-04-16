#🚢 Titanic - Exploratory Data Analysis (EDA)

This project explores the famous Titanic dataset using Python and common data science libraries. The goal is to extract insights and understand the patterns behind passenger survival based on features like age, gender, class, and more.

---

## 📁 Dataset

The dataset used is from the [Kaggle Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic) competition.

- `train.csv`: The main dataset used for analysis.

---

## 🛠️ Tools & Libraries

- **Python** 🐍
- **Pandas** – for data manipulation
- **NumPy** – for numerical operations
- **Matplotlib** & **Seaborn** – for data visualization
- **Jupyter Notebook** – for combining code, visuals, and observations

---

## 📊 EDA Process

### 1. Dataset Overview
- Used `.info()`, `.describe()`, `.value_counts()`, and `.isnull().sum()` to explore structure and missing values.

### 2. Data Cleaning
- Handled missing values in `Age` and `Embarked`.
- Dropped irrelevant columns like `Cabin`, `Ticket`, and `Name`.

### 3. Univariate Analysis
- Countplots and histograms for columns like `Survived`, `Sex`, `Age`, `Fare`, `Pclass`.

### 4. Bivariate/Multivariate Analysis
- Bar plots, violin plots, and heatmaps to show relationships between `Survived` and other features.

### 5. Key Findings
- Women had a significantly higher survival rate.
- 1st class passengers survived more than those in 3rd class.
- Children under 10 also had better survival odds.

---

## 📌 Observations

- **Gender:** Female passengers had much higher survival rates.
- **Class:** First-class passengers had a survival advantage.
- **Age:** Younger passengers were slightly more likely to survive.
- **Fare:** Higher fare passengers tended to survive more.

---

## 📄 Deliverables

- `eda.ipynb` – Jupyter Notebook with code, visuals, and markdown insights.
- `Titanic_EDA_Report.pdf` – PDF version of the analysis report.
- `README.md` – Project documentation (this file).

---

##📬 Contact
For questions or suggestions, feel free to reach out!

