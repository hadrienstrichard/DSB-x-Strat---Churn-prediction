# DSB-x-Strat---Churn-prediction : Client Retention Optimization Project

This project focuses on predicting client churn and optimizing client outreach strategies to improve retention. It consists of two main Jupyter notebooks: `Predicting_churn.ipynb` and `Optimizing_client_reach.ipynb`.

## Installation

To set up the project environment to run the notebooks, follow these steps:

### Requirements

Ensure you have Python installed on your system. This project is tested with Python 3.8. You can download it from [python.org](https://www.python.org/downloads/).

1. Clone or download this repository to your local machine.
2. Navigate to the project directory in your terminal or command prompt.
3. Install the required Python libraries by running:

   ```bash
   pip install -r requirements.txt
   ```

This command will install all the necessary packages, as specified in the requirements.txt file, to ensure compatibility and functionality of the scripts.

### Preparing the Data
The transaction data required for this project is too large for GitHub. Please place the transaction data into the data folder within the project directory.

### Running the Notebooks
#### Predicting_churn.ipynb
**Description**: This notebook performs an analysis on the transaction data to predict which clients are likely to churn. It uses machine learning models to identify patterns and factors that contribute to client churn.

**Output**: The notebook outputs a CSV file containing the churn predictions for each client. This file is saved in the result folder as clients_churn_risk_ranking.csv.
#### Optimizing_client_reach.ipynb
**Description**: This notebook takes the churn predictions and applies optimization algorithms to determine the most effective client reach strategies. It considers factors like cost, impact, and diminishing returns.

**Output**: It produces a CSV file detailing the optimal outreach strategy for each client, considering their predicted churn risk. This file is located in the result folder under optimized_contact_strategies.csv.
Results
