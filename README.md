# Web-page-Phishing-Detection-Using-Deep-Learning

### *The goal of the project is to build a binary classification model to detect phishing web pages using a dataset containing features extracted from URLs.This project employs a PyTorch-based Multi-Layer Perceptron (MLP) for the detection of web page phishing. Through thorough dataset exploration, preprocessing, and neural network architecture design, the code successfully trains an MLP model to classify web pages as either legitimate or phishing.*

## Dataset Exploration:
### a.Explored a dataset with 11,430 instances and 89 features.
### b.Defined phishing as a form of fraud where attackers try to obtain sensitive information through deceptive means.
### c.Encoded the target variable ('status') as binary labels (0 for phishing, 1 for legitimate).

## Data Preprocessing:
### a.Checked for missing values (none found).
### b.Identified categorical columns based on unique value thresholds.
### c.Explored correlations among numerical features.
### d.Visualized distributions of numerical features based on the target variable.

## Neural Network Architecture:
### a.Defined a PyTorch neural network with two hidden layers, batch normalization, ReLU activation, and dropout.
### b.The model takes 87 input features, has 300 nodes in the first hidden layer, 100 nodes in the second hidden layer, and outputs a single node with a sigmoid activation for binary classification.

## Training the Model:
### a.Used binary cross-entropy loss as the loss function.
### b.Employed the Adam optimizer with a learning rate of 0.001.
### c.Trained the model for 50 epochs, monitoring the loss during training.
### d.Plotted the training loss over epochs to visualize model convergence.

## Evaluation Metrics:
### a.Evaluated the trained model on the test set.
### b.Computed and displayed metrics including precision, recall, and F1 score.
### c.Presented the confusion matrix, providing insight into model performance.

## Results:
### a.Achieved good performance on the test set with precision, recall, and F1 score metrics.
### b.The model demonstrated effectiveness in distinguishing between phishing and legitimate web pages.

# Conclusion:
## The project successfully applied deep learning techniques to address the challenge of web page phishing detection. The implemented MLP model demonstrated strong performance, showcasing the potential of neural networks for security-related tasks.
