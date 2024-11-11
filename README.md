# esg-predictor
Training a MLP-NN to predict ESG scores based off company sustainability reports

The dataset and description can be found here: https://www.kaggle.com/datasets/jaidityachopra/esg-sustainability-reports-of-s-and-p-500-companies

NOTE: For this analysis we are treating sustainability reports from the same company in different years as a different "company" or data point for the MLP model to use for training. Since it is a different report and score, treating it as a separate entity from other reports from the same company will provide the model with more data for training, as opposed to focusing on a single year.