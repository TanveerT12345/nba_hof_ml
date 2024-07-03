NBA Player Analysis and Prediction
This project analyzes NBA player statistics to predict the probability of current players being selected for the NBA 75th Anniversary Team. It involves data preprocessing, feature engineering, model training, and evaluation.


To run this project, you need to have the following dependencies installed:
- Python 3.7+
- Jupyter Notebook
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

You can install these dependencies using pip:
pip install pandas numpy scikit-learn matplotlib seaborn

Usage:
To use this project, follow these steps:

1. Clone the repository:
git clone https://github.com/your-username/nba-player-analysis.git

2. Navigate to the project directory:
cd nba-player-analysis

3. Open the Jupyter Notebook:
jupyter notebook nba.ipynb

Run the cells in the notebook to perform data analysis and predictions.

Project Structure:
The project consists of the following files:

- nba.ipynb: Jupyter Notebook containing the analysis and prediction code.
- data/: Directory containing the data files used for analysis.
- README.md: Project documentation.

Data:
The data used in this project includes NBA player statistics from various sources. The key datasets include..

- Player statistics (e.g., points, rebounds, assists)
- Award counts (e.g., MVPs, All-Star selections)
- Player metadata (e.g., name, position, team)

Model:
The project uses logistic regression to predict the probability of players being selected for the NBA 75th Anniversary Team. The steps include...

- Data Preprocessing: Cleaning and preparing the data for analysis.
- Feature Engineering: Creating relevant features from the raw data.
- Model Training: Training a logistic regression model on historical data.
- Model Evaluation: Evaluating the model's performance using metrics such as precision, recall, and ROC-AUC.

Results:
The notebook provides detailed results including...

- Confusion Matrix
- Precision-Recall Curve
- ROC Curve
- Feature Importance
- Predicted probabilities for current players
