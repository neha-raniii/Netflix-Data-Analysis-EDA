# 🎬 Netflix Data Analysis – Exploratory Data Analysis (EDA)

An exploratory data analysis (EDA) project on Netflix's Movies & TV Shows catalog, built in Python using Pandas, NumPy, Matplotlib, and Seaborn. The project cleans the raw dataset and analyzes it to uncover trends in content type, genres, ratings, release years, and countries of production.

## 📌 About the Project

This project walks through a complete EDA workflow on a Netflix titles dataset:

- **Data cleaning** – handling missing values, fixing data types, and standardizing columns
- **Univariate & bivariate analysis** – exploring individual columns and relationships between them
- **Data visualization** – bar charts, count plots, pie charts, and other visuals to surface trends
- **Insight generation** – summarizing patterns in Netflix's content library

All of the analysis and code lives in the Jupyter notebook `Netflix EDA.ipynb`.

## 📂 Repository Structure

```
Netflix-Data-Analysis-EDA/
├── Netflix EDA.ipynb                   # Main Jupyter notebook with the full analysis
├── Netflix-Movies-TVshow-Sample.csv    # Raw/sample dataset
├── netflix_cleaned.csv                 # Cleaned dataset produced during the EDA
├── images/                             # Charts and visuals exported from the notebook
├── requirement.txt                     # Python dependencies
└── README.md
```

## 🛠️ Tech Stack

- **Python 3**
- **Pandas** – data manipulation and cleaning
- **NumPy** – numerical operations
- **Matplotlib** – static plotting
- **Seaborn** – statistical visualizations
- **Jupyter Notebook** – interactive analysis environment

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/neha-raniii/Netflix-Data-Analysis-EDA.git
cd Netflix-Data-Analysis-EDA
```

### 2. Create a virtual environment (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirement.txt
```

### 4. Launch the notebook

```bash
jupyter notebook "Netflix EDA.ipynb"
```

## 🎯 Business Problem

Netflix has a large and diverse content library, but it is important to understand how this content is distributed across different types, genres, countries, ratings, and time periods.

## 🎯 Business Objective

To analyze Netflix's movies and TV shows to understand its content strategy and identify key content patterns and trends.

## 🔍 Key Questions Explored

1. Which type of content is most common on Netflix?
2. Which genres are most common on Netflix?
3. Which countries contribute the most content to Netflix's library?
4. Which content ratings are most common on Netflix?
5. Which years had the highest number of Movies and TV Shows added to Netflix?
6. How has Netflix's content library changed over time?

## 💡 Insights & Recommendations

### Insight 1: Content Type
Movies are more common than TV Shows on Netflix.

**Recommendation:** Netflix can continue adding Movies while also increasing TV Show content when needed.

### Insight 2: Genre
International Movies are the most common category, followed by Dramas and Comedies.

**Recommendation:** Netflix can continue focusing on popular genres while also adding content from other categories.

### Insight 3: Country
The United States contributes the most content to Netflix.

**Recommendation:** Netflix can continue its strong US content while adding more content from other countries.

### Insight 4: Content Rating
TV-MA is the most common rating on Netflix.

**Recommendation:** Netflix can continue providing mature content while also maintaining different types of ratings.

### Insight 5: Content Added by Year
Movie additions peaked in 2019 (~1,420 titles) and TV Show additions peaked in 2020 (~600 titles), though the two peaks are close in timing — both content types saw their strongest year within the 2019–2020 window before declining in 2021.

**Recommendation:** Netflix should monitor yearly content additions and maintain a steady release strategy.

### Insight 6: Content Growth Over Time
Netflix content additions increased significantly after 2015 and reached their highest overall level in 2019.

**Recommendation:** Netflix should continue monitoring content growth and plan future releases based on content demand and trends.

### Insight 7: Directors
Rajiv Chilaka has the highest number of titles among individually credited directors. Note: rows with multiple co-directors (e.g. "Raúl Campos, Jan Suter") were treated as a single combined entry rather than split into individual directors — a possible next step is to explode multi-director rows for a more precise per-director count.

**Recommendation:** Netflix can identify successful directors and consider their past work when planning future content.

Charts and visualizations generated during the analysis are saved in the `images/` folder.

## 📁 Dataset

The dataset used (`Netflix-Movies-TVshow-Sample.csv`) contains metadata about Netflix titles, such as title, type (Movie/TV Show), director, cast, country, date added, release year, rating, and genre listings. After cleaning, the processed version is saved as `netflix_cleaned.csv`.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to check the [issues page](https://github.com/neha-raniii/Netflix-Data-Analysis-EDA/issues) or open a pull request.

## 📄 License

This project currently has no license specified. If you're the repo owner, consider adding one (e.g., MIT) so others know how they can use your work.

## ✍️ Author

**Neha Rani** – [@neha-raniii](https://github.com/neha-raniii)
