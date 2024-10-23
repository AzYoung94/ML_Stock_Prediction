This project contains to Machine learning algorithms for Stock prediction. Below is a desciption of each program.

Linear Regression Script Overview:

Libraries Imported: The script uses pandas, numpy, scikit-learn, and matplotlib.
Data Loading: It loads a dataset into a DataFrame.
Feature Selection: The columns 'Open', 'High', and 'Low' are used as features to predict the 'Close' price.
Train-Test Split: The dataset is split into training and testing sets, with 11.16% of the data reserved for testing (representing the last 28 days of data).
Model Training: A linear regression model is trained using the scikit-learn library.
Model Evaluation: The model's performance is evaluated using mean squared error (MSE).
Plotting: The results of the prediction are plotted to visualize how well the model performs.


Support Vector Machine Script Overview:
Libraries Imported: It uses pandas, scikit-learn, and matplotlib.
Data Loading: Loads the same S&P 500 dataset (S&P500.csv).
Feature Selection: The features 'Open', 'High', and 'Low' are used to predict the 'Close' price.
Train-Test Split: Splits the data into training and testing sets with the same split ratio as before.
Model Training: Trains an SVR model with a Radial Basis Function (RBF) kernel, which is effective for non-linear data.
Model Evaluation: The performance of the SVR model is measured using mean squared error (MSE).
Plotting: Results are visualized using a plot to compare predicted vs actual prices.
