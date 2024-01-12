# Fire-Detector-ML-model
Fire Detection Machine Learning Model
Overview

This repository contains a machine learning model for fire detection based on sensor data. The model utilizes a Decision Tree Classifier and is trained on a dataset consisting of features such as temperature, gas levels, and flame data.
Contents

    Data Loading and Preprocessing: The dataset, stored in "spongeFire.csv," is loaded into a Pandas DataFrame and split into training and testing sets.

    Model Training: A Decision Tree Classifier is created and trained using the training data.

    Model Evaluation: The trained model is evaluated on the testing set, and metrics such as accuracy, a classification report, and a confusion matrix are displayed.

    Hyperparameter Tuning: GridSearchCV is employed to find the optimal hyperparameters for the Decision Tree model, improving its performance.

    Sensitivity Calculation: Sensitivity (Recall) is calculated as an additional evaluation metric.

    Data Visualization: Visualizations using Seaborn and Plotly provide insights into the dataset and the model's predictions.

How to Use

    Clone the repository:

    bash

git clone https://github.com/yihune21/Fire-Detector-ML-model.git
cd fire-detection

Install dependencies:

bash

    pip install -r requirements.txt

    Run the Jupyter Notebook or Python script to train, evaluate, and visualize the model.

Results

The model achieves [mention accuracy/recall/specific metric] and demonstrates [mention any specific patterns or insights].
Future Improvements

[Optional: Mention any planned enhancements, optimizations, or additional features.]
Contributors

    Yihune Zewdie
     

License

This project is licensed under the AASTU License.
