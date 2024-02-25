# Diabetes Prediction Project

This project, named Diabetes Predict, aims to predict the likelihood of an individual having diabetes based on certain health metrics. The prediction model is built using logistic regression, a statistical method commonly used for binary classification tasks like this.

## Dataset

The dataset used in this project is `diabetes.csv`, which contains various health metrics such as glucose level, blood pressure, body mass index (BMI), and other attributes, along with a label indicating whether the individual has diabetes or not. You can download the dataset from [here](https://www.kaggle.com/datasets/saurabh00007/diabetescsv).

## Methodology

1. **Data Preprocessing**: The dataset is preprocessed to handle missing values, normalize features, and split into training and testing sets.

2. **Model Training**: Logistic regression is employed to train the prediction model using the training data.

3. **Model Evaluation**: The trained model's performance is evaluated using metrics such as accuracy, precision, recall, and F1-score on the testing dataset.

4. **Prediction**: Once trained and evaluated, the model is ready to predict the likelihood of diabetes for new individuals based on their health metrics.

## How to Use

1. **Install Required Packages**: Ensure you have all the necessary packages installed. You can install them using the following command:
   ```bash
   pip install -r requirements.txt
   ```

2. **Run the Code**: Execute the main Python script or Jupyter notebook containing the logistic regression model training and prediction code.

3. **Input Health Metrics**: Provide the required health metrics for the individual you want to predict diabetes for.

4. **Get Prediction**: The model will output the likelihood of the individual having diabetes based on the input health metrics.

## Dataset Source

The `diabetes.csv` dataset is obtained from [Kaggle](https://www.kaggle.com/datasets/saurabh00007/diabetescsv), and it is crucial for training and testing the diabetes prediction model.

## Contributors

- Mahesh Sathe (https://github.com/maheshsathe07)

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to contribute to the project or use it for your own purposes following the terms of the license. If you encounter any issues or have suggestions for improvement, please don't hesitate to open an issue or submit a pull request on GitHub.
