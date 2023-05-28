# Detecting Signs of Depression from Social Media Texts

## Description
This project aims to classify signs of depression into three categories: "non-depressed," "moderately depressed," and "severely depressed," based on English-language posts on social media. The classification is performed using Neural Network models, including Convolutional Neural Network (CNN), Gated Recurrent Unit (GRU), and Long Short-Term Memory (LSTM). Additionally, the attention layer weights are utilized to provide justifications and explainability for the classification results.

## Usage
To properly run this project, please follow the instructions below:

1: Run the exploratory data analysis file "Exploratory Data Analysis.ipynb" located in the root directory. This file will provide insights and visualizations of the dataset.

2:Next, execute the pre-processing file "PreProcessing.ipynb" located in the root directory. This step will preprocess the dataset and save the pre-processed test and train sets as pickle files in the "Dataset" repository.

3: Navigate to the "Implementation" directory and run each of the model implementation files ( CNNImplementation.ipynb, GRUImplementation.ipynb, LSTMImplementation.ipynb). These files contain the code for training the models. The trained models will be saved as h5 files in the "Models" repository.

4: Proceed to the "Evaluation" directory and run each of the model evaluation files (CNNEvaluation.ipynb, LSTMEvaluation.ipynb, GRUEvaluation.ipynb). These files will test the trained models and provide evaluation results. The results will be saved as CSV files in the "Results" directory.

5: Finally, run the "ExplainabilityComparison.ipynb" notebook located "Evaluation" in the root directory. This notebook showcases a comparison of the performance of the three models.
