# Predicting Cardiovascular Health with Machine Learning

This project aims to develop a machine learning model to predict the risk of heart disease based on various health parameters. The model utilizes a dataset containing information on attributes such as age, sex, cholesterol levels, and exercise-induced angina, among others.

## Dataset

The dataset used in this project is sourced from Kaggle and contains the following columns:

- age
- sex
- cp (chest pain type)
- trtbps (resting blood pressure)
- chol (serum cholesterol)
- fbs (fasting blood sugar)
- restecg (resting electrocardiographic results)
- thalachh (maximum heart rate achieved)
- exng (exercise induced angina)
- oldpeak (ST depression induced by exercise relative to rest)
- slp (slope of the peak exercise ST segment)
- caa (number of major vessels colored by fluoroscopy)
- thall (thalassemia)
- output (0 - No heart disease, 1 - Heart disease present)

The dataset can be downloaded from [Kaggle](https://www.kaggle.com/datasets/suryaabd/heartattack-prediction-using-svmclassifer/data).

## Getting Started

To run this project locally, follow these steps:

1. Clone this repository.
2. Install the required dependencies specified in the `requirements.txt` file.
3. Download the dataset from the provided link and place it in the project directory.
4. Run the `heart_disease_prediction.ipynb` notebook using Jupyter Notebook or any compatible environment.

## Dependencies

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Usage

The main file of interest is `heart_disease_prediction.ipynb`, which contains the entire machine learning pipeline, including data loading, preprocessing, model training, evaluation, and interpretation.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Dataset Source: [Kaggle - Heart Attack Prediction](https://www.kaggle.com/datasets/suryaabd/heartattack-prediction-using-svmclassifer/data)

