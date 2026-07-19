# Netflix Data Analysis & Content Recommendation | Machine Learning Project

## 📋 Project Overview
This project explores Netflix's content library (Movies & TV Shows) to uncover trends in genres, countries, release years, and ratings. It also includes attempts at building predictive models for content rating classification.

**Objectives:**
- Perform comprehensive EDA on Netflix data
- Analyze content distribution by type, genre, country, and year
- Identify top directors, popular genres, and release trends
- Build classification/regression models for rating prediction

## 📊 Dataset
- **Filename**: `netflix_data.csv`
- **Rows**: 8,790
- **Columns**: 10

**Key Features:**
- `show_id`, `type` (Movie / TV Show)
- `title`, `director`, `country`
- `date_added`, `release_year`
- `rating`, `duration`
- `listed_in` (Genres)

## 🛠 Data Preprocessing
- Checked for missing values (None found)
- Verified no duplicate rows
- Extracted new features:
  - Genre (from `listed_in`)
  - Month & Year of addition
  - Weekend vs Weekday addition
- Data type validation and cleaning

## 📈 Exploratory Data Analysis Highlights
- Distribution of Movies vs TV Shows
- Top 10 Genres, Countries, and Directors
- Content release trends over the years
- Rating distribution analysis
- Most popular months for content addition
- Relationship between genre, country, and rating

## 🤖 Machine Learning Models
- Train-Test Split (80:20)
- Feature Selection (`type`, `title`, `country`, `director`, `genre`)
- Models Implemented:
  - Logistic Regression
  - Linear Regression (for experimentation)
- Target Variable: `rating`

## 🛠 Technologies Used
- **Python 3.12**
- **Pandas & NumPy** – Data Manipulation
- **Matplotlib & Seaborn** – Data Visualization
- **Scikit-learn** – Machine Learning & Model Evaluation

   ```bash
   git clone https://github.com/yourusername/netflix-data-analysis.git
   cd netflix-data-analysis
