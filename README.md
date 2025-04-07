# task-1-data-cleaning-
# 📺 Netflix Data Cleaning Project
This project focuses on cleaning a real-world Netflix dataset using **Python** in a **Jupyter Notebook** environment. The cleaning process is performed step-by-step to prepare the data for further analysis or visualization.
## 📌 Objectives
- Load and explore the raw Netflix dataset  
- Identify and handle missing values  
- Remove duplicates  
- Standardize data types and formats
- transformed data
- Clean specific columns like `rating`, `show_id`, `date_added`.
- ## 📒 Notebook Used

- `task1.ipynb` – Main notebook where all data cleaning steps are performed

## 🛠️ Tools & Libraries

- Python 3  
- Jupyter Notebook  
- Pandas  
- NumPy

- ## 📂 Dataset Overview

The dataset includes information on Netflix titles, such as:

- Title  
- Type (Movie/TV Show)  
- Director  
- Cast  
- Country  
- Date Added  
- Release Year  
- Rating  
- Duration  
- Genre  
- Description

- ## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/netflix-data-cleaning.git
   cd netflix-data-cleaning
   ```

2. **Install dependencies:**
   ```bash
   pip install pandas numpy jupyter
   ```

3. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

4. Open `task1.ipynb` and run through the cells.

## ✅ Cleaning Highlights

- Dropped rows with missing or null values where appropriate  
- Converted `date_added` to `datetime` format  
- Stripped extra whitespace and standardized strings  
- Parsed `duration` into numeric values and units

## 📊 Ready for

- Exploratory Data Analysis (EDA)  
- Visualization Dashboards  
- Recommendation Systems  
- Time Series Analysis

## 📄 License

Open source under the [MIT License](LICENSE).
