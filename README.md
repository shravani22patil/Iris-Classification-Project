🎯 Project Overview

This project implements a foundational machine learning classification model using the famous Iris dataset. 

The goal is to predict the species of Iris flower (Setosa, Versicolor, or Virginica) based on its sepal and petal dimensions.

We used the Decision Tree Classifier model, known for its high interpretability and efficiency on small, well-separated datasets.

✨ Key Achievement

The model achieved an outstanding 100% accuracy on the unseen test data, demonstrating perfect classification capability for this dataset.

🛠️ Technology Stack 

Language: Python
Data Manipulation: pandas

Machine Learning: scikit-learn (sklearn)

Data Visualization: matplotlib, seaborn, graphviz (for tree structure)

📁 Repository Structure

├── IRIS.csv                 # The dataset used for training and testing.

├── iris_classification.py   # Main Python script containing the model logic.

├── README.md                # This file.

├── assets/

│   ├── iris_scatter_plot.png  # Visualization of feature separation.

│   └── decision_tree_viz.png  # Visualization of the model structure.

└── Iris_Classification.ipynb  # (Optional) The Colab Notebook file.

⚙️ Setup and Installation

Clone the Repository:Bashgit clone <YOUR_REPO_URL>
cd <YOUR_REPO_NAME>

Install Dependencies:It is recommended to use a virtual environment.Bash# Create and activate a virtual environment (optional but recommended)

python -m venv venv

source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

# Install required packages
pip install pandas scikit-learn matplotlib seaborn graphviz

Run the Script:Ensure IRIS.csv is in the root directory, then run:Bashpython iris_classification.py

📊 Results and EvaluationThe dataset was split into 70% for training and 30% for testing. 

The resulting model performance is summarized below:MetricValueModelDecision Tree ClassifierTest Set Size45 samplesAccuracy Score$\mathbf{1.0000}$ (100%)

The high accuracy indicates that the four features (sepal_length, sepal_width, petal_length, petal_width) provide sufficient information for perfect discrimination between the three species in the test set.
