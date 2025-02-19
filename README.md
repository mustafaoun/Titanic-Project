# Titanic Dataset Analysis & Prediction Project

## Project Overview
This project is an exploratory data analysis (EDA) and machine learning model development exercise using the Titanic dataset. The goal is to analyze the dataset, extract insights, and build a predictive model to determine the survival of passengers based on various features.

## Dataset Description
The Titanic dataset is a classic dataset used for binary classification tasks. It contains information about passengers, such as age, gender, ticket class, and whether they survived the sinking of the Titanic.

### Key Features:
- **PassengerId**: Unique identifier for each passenger.
- **Survived**: Survival status (0 = No, 1 = Yes).
- **Pclass**: Ticket class (1st, 2nd, 3rd).
- **Name**: Passenger name.
- **Sex**: Gender.
- **Age**: Age in years.
- **SibSp**: Number of siblings/spouses aboard.
- **Parch**: Number of parents/children aboard.
- **Ticket**: Ticket number.
- **Fare**: Passenger fare.
- **Cabin**: Cabin number.
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

## Project Steps
1. **Data Exploration & Visualization:**
   - Analyzed missing values.
   - Visualized survival rates based on gender, class, and other features.
   - Explored correlations between features.

2. **Data Cleaning & Preprocessing:**
   - Handled missing values.
   - Converted categorical data into numerical form.
   - Scaled numerical features.

3. **Model Building:**
   - Used machine learning algorithms like Logistic Regression, Decision Trees, and Random Forest.
   - Evaluated model performance using accuracy, precision, recall, and F1-score.

## Key Insights
- Women had a higher survival rate compared to men.
- Passengers in higher classes had a better chance of survival.
- Families traveling together had a different survival pattern compared to individuals traveling alone.

## Results
- Achieved an accuracy of **XX%** using the best-performing model.

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/Titanic-Dataset-Analysis.git
   ```
2. Navigate to the project folder:
   ```bash
   cd Titanic-Dataset-Analysis
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook or Python scripts.

## Repository Structure
```
Titanic-Dataset-Analysis/
│
├── data/                    # Dataset files
├── notebooks/               # Jupyter notebooks
├── scripts/                 # Python scripts
├── images/                  # Visualizations
└── README.md
```

## Future Improvements
- Experiment with more advanced models like XGBoost and SVM.
- Perform hyperparameter tuning for better performance.
- Engineer more features from the existing data.

## Contact
Feel free to reach out for any questions or suggestions:
- **LinkedIn:** [Your LinkedIn Profile]([https://www.linkedin.com/in/mustafa-oun/])
- **GitHub:** [Your GitHub Profile](https://github.com/mustafaoun)

## License
This project is open-source and available under the [MIT License](LICENSE).

