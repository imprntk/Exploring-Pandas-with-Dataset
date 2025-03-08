Exploring Pandas with Kaggle Datasets

📌 Overview

This repository contains various Pandas operations for exploring, analyzing, and manipulating datasets downloaded from Kaggle. The project demonstrates data cleaning, transformation, aggregation, and visualization techniques using real-world datasets.

🔧 Features

1️⃣ Downloading and Loading Kaggle Datasets

Download datasets from Kaggle and place them in the data/ folder.

Loading CSV Files:

df = pd.read_csv("data/kaggle_dataset.csv")

2️⃣ Data Cleaning and Preprocessing

Renaming columns for better readability.

Handling missing values by filling or dropping them.

Converting data types (e.g., datetime conversion).

Removing duplicate entries.

3️⃣ Handling Missing Values

Checking for missing values:

print(df.isnull().sum())

Filling missing values with appropriate replacements.

Dropping rows with missing values.

4️⃣ Exploratory Data Analysis (EDA)

Generating summary statistics:

print(df.describe())

Checking correlations between features:

print(df.corr())

Grouping and aggregating data for insights.

5️⃣ Data Transformation

Applying functions to transform data.

Creating new columns based on existing ones.

Replacing values for better data consistency.

📂 Project Structure

/Learning Insights Using Pandas
│── data                   # Kaggle datasets              
│   ├── bios.csv        # Script to load datasets
│   ├── noc_regions.csv       # Data cleaning operations
│   ├── olympics_data
│   ├── results..csv       # Script to load datasets
│── warm-up data
│   ├── coffee.csv        # Script to load datasets
│   ├── dataframe.ipynb       # Data cleaning operations
│── README.md               # Documentation
│── requirements.txt        # Dependencies

🛠️ Installation

Clone the repository:

git clone https://github.com/imprntk/Exploring-Pandas-With-Dataset

Create a virtual environment (optional):

python -m venv venv
source venv/bin/activate   # On Windows use: venv\Scripts\activate

Install dependencies:

pip install -r requirements.txt

📜 License

This project is licensed under the MIT License.

🚀 Happy Exploring! 🎯

