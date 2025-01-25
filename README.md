# Diwali Sales Analysis Python Project

## Objective
The primary goal of this project is to analyze sales data around the Diwali festival period to uncover insights into customer buying patterns, product preferences, and demographic influences on purchasing behavior.

## Tools and Technologies Used
- **Programming Language:** Python
- **Libraries:**
  - Pandas: For data manipulation
  - NumPy: For numerical operations and array manipulations
  - Matplotlib: For data visualization
  - Seaborn: For enhanced data visualization

## Methodology

### 1. Importing Libraries
Utilized Python libraries such as Pandas for data manipulation and Matplotlib/Seaborn for visualization to prepare the environment for analysis.

### 2. Loading Dataset
Loaded the sales data from a CSV file, which provided the foundation for our analysis. The dataset included:
- Customer demographics
- Product categories
- Purchase amounts

### 3. Data Information and Structure
Examined the dataset to understand its structure:
- Checked the number of rows and columns
- Reviewed data types
- Conducted a preliminary check for missing values

### 4. Data Cleaning
- Addressed missing values
- Removed duplicates
- Corrected data types to ensure the integrity of the analysis

### 5. Exploratory Data Analysis (EDA)
Conducted a thorough exploration of the data, focusing on:
- **Gender:** Analyzed sales data by gender to identify purchasing trends.
- **Age:** Investigated how different age groups contributed to sales.
- **State:** Examined sales distribution across different states.
- **Marital Status:** Explored the impact of marital status on purchasing behavior.
- **Occupation:** Analyzed how occupation influences buying patterns.
- **Product Category:** Identified the most popular product categories during the Diwali sales period.

## Conclusion
The analysis revealed that married women aged 26-35 years from Uttar Pradesh, Maharashtra, and Karnataka working in IT, Healthcare, and Aviation are more likely to purchase products from the following categories:
- Food
- Clothing
- Electronics

## Skills Demonstrated
- Python (Programming Language)
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn

## How to Run the Project
1. Clone this repository to your local machine.
2. Ensure you have Python installed along with the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Load the dataset (ensure the file path is correctly set in the script).
4. Run the analysis script in a Jupyter Notebook or any Python IDE.

## Project Structure
- `data/`: Contains the dataset (CSV file).
- `notebooks/`: Jupyter Notebooks for analysis.
- `images/`: Visualizations and plots generated during EDA.
- `README.md`: Project documentation.
