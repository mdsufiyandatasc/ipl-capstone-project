# ipl-capstone-project
# 🏏Exploratory Data Analysis using Python

## 📌 Project Description
This project is a **comprehensive Exploratory Data Analysis (EDA)** of the **Indian Premier League (IPL)** dataset, implemented using **Python in a Jupyter Notebook**.  
The goal of this project is to analyze IPL match and player data to extract meaningful insights related to **team performance, player statistics, toss impact, venue influence, and bowling achievements**.

The project reflects real-world data analysis practices including **data cleaning, feature extraction, aggregation, and visualization**.

---

## 📂 Dataset Overview
The dataset used in this project contains information related to:
- Match details (match ID, venue, teams)
- Toss winner and match winner
- Player performance statistics
- Bowling figures and wickets
- Venue-wise match outcomes

The dataset required preprocessing due to **inconsistent formats and mixed data types**, which makes it suitable for practicing real-world data handling.

---

## 🛠️ Tools & Technologies Used
- **Python**
- **Jupyter Notebook**
- **Pandas** – data manipulation and aggregation
- **NumPy** – numerical computations
- **Matplotlib** – basic visualizations
- **Seaborn** – advanced and statistical visualizations

---

## 📁 Project Structure
ipl-capstone-project/
│
├── IPL_Capstone_Project.ipynb # Main Jupyter Notebook
├── data/ # Dataset files (if applicable)
├── images/ # Saved charts (optional)
└── README.md # Project documentation

---

## 🔍 Analysis Performed

### 1️⃣ Loading Libraries and Dataset
- Imported required Python libraries
- Loaded the IPL dataset into Pandas DataFrame
- Verified dataset structure and columns

---

### 2️⃣ Basic Information Analysis
- Checked dataset shape and data types
- Identified missing and inconsistent values
- Explored overall match statistics

---

### 3️⃣ Key Player Performances
- Extracted **wickets from bowling figures**
- Cleaned string-based statistics into numerical values
- Identified top bowlers based on total wickets
- Grouped and aggregated player performance metrics

---

### 4️⃣ Venue Analysis
- Analyzed match outcomes across different venues
- Studied how venues influence match results
- Compared venue-wise performance trends

---

### 5️⃣ Toss Impact Analysis
- Analyzed how often the **toss winner also wins the match**
- Evaluated the strategic importance of toss decisions
- Calculated match-winning probabilities based on toss outcomes

---

### 6️⃣ Custom Questions & Insights
- Answered custom analytical questions using:
  - `groupby`
  - `sum`, `count`
  - sorting and filtering
- Derived meaningful cricket insights using data-driven logic

---

## 📊 Visualizations
The project includes multiple visualizations such as:
- Bar charts for team and player comparisons
- Count plots for categorical analysis
- Statistical plots using Seaborn palettes

These visualizations help communicate trends and patterns clearly.

---

## 📈 Key Insights
- Toss decisions have a measurable impact on match outcomes
- Certain players consistently outperform others in bowling
- Venue plays a significant role in determining match results
- Cleaned and structured data leads to more accurate insights
🎯 Learning Outcomes

Hands-on experience with real-world messy datasets

Strong understanding of EDA workflow

Improved skills in data cleaning and feature engineering

Practical usage of Pandas aggregation and visualization

Ability to extract and communicate insights effectively

👤 Author

Mohammad Sufiyan
Aspiring Data Analyst | Data Science Enthusiast

📜 License

This project is created for educational and learning purposes only.
