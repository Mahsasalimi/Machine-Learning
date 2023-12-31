# Combined Cycle Power Plant Data Analysis
This project analyzes a dataset containing 9568 data points collected from a Combined Cycle Power Plant over 6 years (2006-2011). The dataset includes hourly average ambient variables such as Average Temperature (AT), Ambient Pressure (AP), Relative Humidity (RH), and Exhaust Vacuum (V), which are used to predict the net hourly electrical energy output (EP) of the plant. The dataset was collected when the power plant was set to work with full load.

A combined cycle power plant (CCPP) is composed of gas turbines (GT), steam turbines (ST), and heat recovery steam generators. In a CCPP, the electricity is generated by gas and steam turbines, which are combined in one cycle, and is transferred from one turbine to another. While the Vacuum is collected from and has an effect on the Steam Turbine, the other three of the ambient variables affect the GT performance.

The attribute information for the dataset is as follows:

- Temperature (T) in the range 1.81°C and 37.11°C
- Ambient Pressure (AP) in the range 992.89-1033.30 milibar
- Relative Humidity (RH) in the range 25.56% to 100.16%
- Exhaust Vacuum (V) in the range 25.36-81.56 cm Hg
- Net hourly electrical energy output (EP) 420.26-495.76 MW
- The averages are taken from various sensors located around the plant that record the ambient variables every second. The variables are given without normalization.

# Regression Models
This project uses three different regression models to predict the net hourly electrical energy output of the power plant:

1. Simple Regression Model: This model uses a single input variable to predict the output variable. In this case, we use Ambient Temperature (AT) as the input variable and the Net Hourly Electrical Energy Output (EP) as the output variable.

2. Polynomial Regression Model: This model fits a polynomial equation to the data in order to model the relationship between the input and output variables. In this case, we use Ambient Temperature (AT) as the input variables and the Net Hourly Electrical Energy Output (EP) as the output variable.

3. Multiple Regression Model: This model uses multiple input variables to predict the output variable. In this case, we use all four ambient variables (AT, AP, RH, and V) as the input variables and the Net Hourly Electrical Energy Output (EP) as the output variable.

# Usage
To run this project, you will need to have Python installed on your computer. You can download Python from the official website.

1. Clone the repository to your local machine.
2. Install the required packages using pip:
`
pip install -r requirements.txt --ignore-installed
`
3. Run the Python script:
`
 Regression.py
`
4. Follow the prompts to select the regression model you want to use and view the results.

# Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request.

# License
This project is licensed under the MIT License.
