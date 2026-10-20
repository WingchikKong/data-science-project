# Impact of Education on Annual Salary and Weekly Working Hours

## 1. The problem or research question
This project aims to investigate whether a person's education level has an influence on their annual salary and weekly working hours, using data from 500 people in New York State.

## 2. Dataset source and usage permissions
- **Source:** American Community Survey (ACS) Public-Use Microdata Samples (PUMS) dataset (2017 one-year estimate).
- **Permissions:** This dataset is publicly available for educational and analytical purposes.

## 3. Methods and tools used
- **Languages & Libraries:** Python, Pandas, Matplotlib, Seaborn, Squarify.
- **Methods:** Exploratory Data Analysis (EDA), data filtering (excluding people >= 65 years old), and data visualization (Tree map and Violin plots).

## 4. Key findings and one limitation
- **Key findings:** 
  1. The Tree map shows that the majority of the sample has a Bachelor's degree or higher (47.4%), followed by High school diploma (21.4%).
  2. The Violin plots indicate that people with a Bachelor's degree or higher tend to have a higher annual salary, but their weekly working hours are relatively concentrated around 40 hours, similar to other groups.
- **Limitation:** The dataset only contains 500 samples from New York State, which may not fully represent the broader population. Additionally, salary data contains many "0" values which might represent unemployed or retired individuals, potentially skewing the lower end of the distribution.

## 5. Instructions for running the analysis
1. Clone this repository.
2. Install the required packages: `pip install -r requirements.txt`
3. Open the `MC653910_Activity7.06.ipynb` file in Jupyter Notebook.
4. Ensure `age_salary_hours.csv` is in the same directory, and run all cells.
