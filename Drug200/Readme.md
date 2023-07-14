# Drug Classification
## Introduction
This repository contains code and a dataset for classifying drugs based on various patient features. The goal is to train a decision tree model to accurately predict the drug type for a given patient using their age, sex, blood pressure, cholesterol levels, and sodium to potassium ratio in the blood.

## Dataset
The dataset used for this classification task is stored in the drug200.csv file. It includes the following columns:

1. Age: Age of the patient
2. Sex: Gender of the patient
3. BP: Blood pressure levels
4. Cholesterol: Cholesterol levels
5. Na_to_K: Sodium to potassium ratio in the blood
6. Drug: The type of drug the patient responded to (target variable)

## Requirements
The following dependencies are required to run the project:

- Python (version 3.6 or higher)
- Libraries: pandas, numpy, scikit-learn, seaborn, matplotlib, plotly
You can install the dependencies using pip:
``pip install pandas numpy scikit-learn seaborn matplotlib plotly``

Make sure to use Python version 3.6 or higher and install the specified library versions.


## Code
The provided Jupyter Notebook file, Drug200.ipynb, contains the code for performing data exploration, pre-processing, modeling, and result visualization. The code utilizes various libraries such as pandas, numpy, scikit-learn, seaborn, and matplotlib for data manipulation, machine learning modeling, and visualization.

## Usage
1. Clone the repository to your local machine.
2. Install the required dependencies using the above command.
3. Launch Jupyter Notebook and open the `drug200.ipynb` file.
4. Execute the main script or run the Jupyter Notebook to reproduce the results.
5. Review the output, including data exploration visualizations, model accuracy, and the decision tree visualization.

## Results
After running the code, you will obtain the accuracy score of the decision tree model in classifying the drug data. Additionally, the notebook provides visualizations to explore the dataset and understand the relationships between the features and the drug types.

## Conclusion
By utilizing the provided dataset and code, you can gain insights into drug classification based on patient features using decision tree modeling. Feel free to experiment with different algorithms, parameter settings, and visualization techniques to further improve the drug classification task.

## License
This project is licensed under the [MIT License](LICENSE).

