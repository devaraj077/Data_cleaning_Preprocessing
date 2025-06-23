# AI/ML Internship - Task 1: Data Cleaning & Preprocessing

## Objective
Clean and prepare raw data for machine learning using techniques like handling missing values, encoding categorical variables, feature scaling, and outlier detection.

## Files Included
- `titanic-2.py` – Google colab code with full preprocessing steps  
- `cleaned_titanic.csv` – Cleaned dataset after preprocessing  
- `plots/` folder – Contains visualizations like correlation heatmap and boxplot  
- `README.md` – This file (explains what the repo contains)
- `Titanic_Dataset.csv` - Original dataset before preprocessing 

## Tools & Libraries
- Python
- Pandas – for data manipulation
- NumPy – for numerical operations
- Matplotlib / Seaborn – for visualization
- Google Colab – for running code
- GitHub – for version control

## Dataset
- [Titanic Dataset](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv) 
Includes features like:
- PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked

## Steps Performed
1. Checked and handled missing values in `Age`, `Embarked`, and dropped `Cabin`.
2. Encoded categorical variables (`Sex`, `Embarked`) using one-hot encoding.
3. Standardized numerical features (`Age`, `Fare`, `SibSp`, `Parch`).
4. Detected and removed outliers in `Fare` using IQR method.
5. Visualized data patterns using plots.

## Visualizations
### Correlation Heatmap
![Correlation Heatmap](plots/correlation_heatmap.png)
### Fare Boxplot (Outliers)
![Fare Boxplot](plots/fare_boxplot.png)

## How to Run
1. Clone repo
2. Install libraries
3. Run notebook
