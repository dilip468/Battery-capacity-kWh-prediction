🧠 Project Title
Decision Tree Classification on the Iris Dataset

🎯 Objective
To build a machine learning model using a Decision Tree Classifier that can predict the species of an Iris flower based on its sepal and petal dimensions.

📊 Dataset
Source: Built-in Iris dataset from sklearn.datasets

Features:

Sepal Length (cm)

Sepal Width (cm)

Petal Length (cm)

Petal Width (cm)

Target classes:

Setosa (0)

Versicolor (1)

Virginica (2)

⚙️ Technologies Used
Python 3.x

Jupyter Notebook

pandas

scikit-learn

🔍 Steps Performed
Import Libraries:
Loaded essential libraries like pandas, sklearn, etc.

Load Dataset:
Loaded the Iris dataset and separated features (X) and labels (y).

Split Dataset:
Used train_test_split() to split the dataset into training and testing sets (80/20).

Train Model:
Trained a DecisionTreeClassifier on the training data.

Make Predictions:
Predicted the labels for the test set.

Evaluate Model:
Compared actual vs. predicted labels and calculated accuracy using accuracy_score.

📈 Output
A table showing actual vs predicted labels

Accuracy Score printed to console (e.g., Accuracy: 0.97)

✅ Conclusion
The Decision Tree model performed with high accuracy on the Iris dataset, demonstrating its effectiveness in basic classification tasks.

📁 Files Included
project python (7).ipynb – Main Jupyter notebook with all code

README.md – Description and instructions (this file)
