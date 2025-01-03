# Titanic Survival Prediction

This project aims to predict the survival of passengers on the Titanic using various machine learning models. The dataset used for this project is the famous Titanic dataset from Kaggle.

## Project Structure

```
titanic-survival-prediction
├─ data
│ ├─ test.csv
│ └─ train.csv
├─ README.md
└─ Titanic.ipynb
```

- `data/`: Contains the dataset files.
- `Titanic.ipynb`: Jupyter notebook with the data analysis, preprocessing, and model training.

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/huylys54/Titanic-Survival-Prediction.git
   cd titanic-survival-prediction
   ```

2. Create a virtual environment and activate it:

   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. Open the Jupyter notebook:

   ```sh
   jupyter notebook Titanic.ipynb
   ```

2. Run the cells in the notebook to perform data analysis, preprocessing, and model training.

## Models Used

- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Gradient Boosting
- AdaBoost

## Evaluation

The models are evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1 Score

## Results

The results of the models are displayed in the notebook, including the evaluation metrics and feature importance scores.

## Contributors

- Lê Hoàng Khang
- Lý Hoàng Gia Huy
- Dương Hải Minh

## License

This project is licensed under the MIT License.
