# Data Cleaning And Preprocessing
Using Python, Pandas, NumPy, Matplotlib/Seaborn, Scikit-Learn to clean and prepare Titanic dataset for analysis.

# Tools Used

Python
Pandas
NumPy
Matplotlib / Seaborn
Scikit-Learn 

# Dataset
Titanic Dataset (Kaggle: https://www.kaggle.com/datasets/yasserh/titanic-dataset )

# Task Breakdown

1. Import & Explore the Dataset

- Load the dataset using pandas 
- Explore the dataset using .info(), .head(), and .describe()

2️. Handle Missing Values

- Identify nulls using .isnull().sum().
- Fill missing numerical columns using mean or mode.

3. Encode Categorical Features

- Convert text-based columns like sex and embarked  into numeric format.
- Use map() or pd.get_dummies() for encoding.

4️. Normalize/Standardize Numerical Features

- Standardize features like Age and Fare using StandardScaler from Scikit-Learn.

5️. Visualize & Remove Outliers

- Use seaborn.boxplot() to visualize outliers in numerical columns.
- Apply IQR method to remove rows with extreme values.

# Output

- Cleaned DataFrame ready for further analysis using ML algorithms.
- Boxplots showing data before and after outlier removal.
- DataFrame saved to .CSV file
