# Titanic Survival Prediction

## 📝 Overview
This project is focused on **predicting survival on the Titanic** based on a set of features like **age, sex, class, fare,** and **embarkation port** using machine learning models. The goal is to predict whether a passenger survived or not during the Titanic disaster. The project implements **data preprocessing**, **model training**, and **evaluation**.

---

## 📊 Dataset
The dataset used for this project is from the **Kaggle Titanic Challenge**. It includes the following columns:

- **PassengerId**: Unique identifier for each passenger
- **Survived**: Whether the passenger survived (1) or not (0)
- **Pclass**: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Name**: Name of the passenger
- **Sex**: Gender of the passenger
- **Age**: Age of the passenger
- **SibSp**: Number of siblings or spouses aboard
- **Parch**: Number of parents or children aboard
- **Ticket**: Ticket number
- **Fare**: Fare paid by the passenger
- **Cabin**: Cabin number (may have missing values)
- **Embarked**: Embarkation port (C = Cherbourg, Q = Queenstown, S = Southampton)

---

## ⚙️ Steps Involved

### 1. **Data Preprocessing**
   - Handle missing values (e.g., filling missing `Age` values with median, encoding `Sex` and `Embarked` columns).
   - Drop irrelevant columns like `Name`, `Ticket`, and `Cabin`.
   - Convert categorical variables into numeric format using **Label Encoding** or **One-Hot Encoding**.

### 2. **Modeling**
   - Split the dataset into training and test sets.
   - Train various machine learning models (e.g., **Logistic Regression**, **Random Forest**, or **Neural Networks**).
   - Evaluate model performance using accuracy, precision, recall, and F1-score.

### 3. **Neural Network**
   - A simple neural network is implemented with **PyTorch** for binary classification.
   - The neural network includes layers, activation functions, and is trained using **BCELoss** for binary classification.

---

## 🔨 Requirements

- **Python 3.x**
- **Pandas**: For data manipulation
- **NumPy**: For numerical operations
- **Scikit-learn**: For machine learning algorithms and evaluation
- **PyTorch**: For neural network modeling (optional, if using NN)
- **Matplotlib** and **Seaborn**: For data visualization (optional)

You can install the necessary libraries using `pip`:

```bash
pip install pandas numpy scikit-learn torch matplotlib seaborn
```

---

## 🧑‍💻 Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/titanic-survival-prediction.git
   cd titanic-survival-prediction
   ```

2. **Data Preprocessing**:
   - Run the `preprocess.py` script to clean and prepare the Titanic dataset.

3. **Model Training**:
   - Train your models using the `train_model.py` script.
   - Use the neural network model by running `train_neural_net.py` if you wish to use a neural network approach.

4. **Evaluate the Model**:
   - After training, evaluate the model on the test set using `evaluate_model.py`.

5. **Make Predictions**:
   - Use the trained model to predict survival for new data.

---

## 📈 Results
The model achieves an accuracy of **X%** on the test set, and the **Logistic Regression** model performs well with **X** as the best classification metric (e.g., F1-score, accuracy).

---

## 🎯 Future Work
- Experiment with **Hyperparameter Tuning** to improve the model.
- Try additional models, such as **XGBoost** or **SVM**.
- Add **cross-validation** to ensure robustness of the model.
- Explore **ensemble methods** to combine predictions from multiple models.

---

## 🛠️ Files

- `preprocess.py`: Data preprocessing steps.
- `train_model.py`: Script to train machine learning models.
- `train_neural_net.py`: Neural network training script.
- `evaluate_model.py`: Script to evaluate model performance.
- `Titanic.csv`: Titanic dataset file.

---

## 📬 Contact

For questions, feel free to reach out to me via [s4shubham1605@gmail.com](mailto:s4shubham1605@gmail.com).

---

### 📌 Example Workflow:

```bash
# Clone the repo
git clone https://github.com/yourusername/titanic-survival-prediction.git

# Navigate to the folder
cd titanic-survival-prediction

# Preprocess data
python preprocess.py

# Train a model
python train_model.py

# Evaluate the model
python evaluate_model.py
```

---
