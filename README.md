# Data-cleaning-project 

📌 About the project

This project focuses on cleaning and preprocessing a laptop dataset using Python. The raw dataset contained inconsistent data formats, unnecessary columns, and categorical values that required transformation before analysis.

The goal was to convert the dataset into a clean, structured, and analysis-ready format following standard data preprocessing practices.


📂 Dataset

- Dataset: Laptop Price Dataset
- File Format: CSV
- Language: Python
- Environment: Jupyter Notebook


🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn


🔍 Data Cleaning Performed

- Loaded and explored the dataset.
- Checked dataset structure using "info()" and "shape".
- Identified duplicate records.
- Checked for missing values.
- Removed unnecessary columns (e.g., "Unnamed: 0").
- Cleaned the RAM column by removing ""GB"" and converting it to integer.
- Cleaned the Weight column by removing ""kg"" and converting it to float.
- Verified data types after cleaning.
- Prepared the dataset for further analysis and machine learning.


📊 Exploratory Data Analysis (EDA)

The project also includes visualizations such as:

- RAM distribution
- RAM vs Price (Strip Plot)
- Average Price by RAM
- Box Plot of RAM vs Price
- Weight distribution
- Weight vs Price
- Price distribution histogram


📈 Key Insights

- Most laptops have 1–2.7 kg weight.
- Higher RAM configurations generally have higher average prices.
- The average laptop price is approximately ₹60,000, while the median price is around ₹52,000.
  

📁 Project Structure

├── Data_cleaning_project.ipynb
├── laptop_data.csv
└── README.md


🚀 How to Run

1. Clone the repository.
2. Install the required libraries:
   pip install pandas numpy matplotlib seaborn scikit-learn
3. Open "Data_cleaning_project.ipynb" in Jupyter Notebook or Google Colab.
4. Run the notebook cells sequentially.


🎯 Project Objective

To demonstrate practical data cleaning, preprocessing, and exploratory data analysis skills using Python, preparing raw data for accurate analysis and machine learning applications.


👨‍💻 Author
Khushi Singh
