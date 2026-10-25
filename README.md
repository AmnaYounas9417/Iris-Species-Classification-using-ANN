# Iris Species Classification using Artificial Neural Network (ANN)

## Project Overview
This project uses an Artificial Neural Network (ANN) built with TensorFlow/Keras to classify Iris flowers into three species: Setosa, Versicolor, and Virginica.

The model predicts the species based on four flower measurements: sepal length, sepal width, petal length, and petal width.

## Dataset
The project uses the classic Iris dataset, containing measurements of Iris flowers from three species.

**Input Features:**
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

**Target Classes:**
- Setosa
- Versicolor
- Virginica

## Technologies Used
- Python
- TensorFlow / Keras
- Scikit-learn
- NumPy
- Pandas
- Matplotlib
- Seaborn

## Project Workflow
1. Load and explore the Iris dataset.
2. Encode the species labels using LabelEncoder.
3. Split the data into training and testing sets using stratified sampling.
4. Standardize the input features using StandardScaler.
5. Convert target labels to categorical format.
6. Build an ANN using TensorFlow/Keras.
7. Train the model using the Adam optimizer and categorical cross-entropy loss.
8. Evaluate model performance on the test dataset.
9. Visualize training and validation accuracy and loss.

## ANN Architecture
- **Input Layer:** 4 input features
- **Hidden Layer 1:** 16 neurons with ReLU activation
- **Hidden Layer 2:** 8 neurons with ReLU activation
- **Output Layer:** 3 neurons with Softmax activation

**Training Configuration:**
- Optimizer: Adam
- Loss Function: Categorical Cross-Entropy
- Epochs: 100
- Batch Size: 8
- Validation Split: 20%

## Results

| Metric | Result |
|---|---:|
| Test Accuracy | 93.33% |
| Test Loss | 0.110 |

The model achieved 93.33% test accuracy on the held-out test dataset.

## Visualizations
The notebook includes:
- Training and validation accuracy curves
- Training and validation loss curves

These visualizations help track the learning process and assess model performance.

## How to Run
1. Open the notebook in Google Colab.
2. Run the cells in order.
3. Review the model training results and evaluation plots.

## Future Improvements
- Experiment with different ANN architectures.
- Tune hyperparameters to improve performance.
- Compare different activation functions and optimizers.
- Add a simple interface for predicting Iris species from user-provided measurements.

## Author
Created as a Machine Learning and Deep Learning portfolio project.
