## MNIST Handwritten Digits Classification with Random Forest

#### Table of Contents
- Description
- Installation
- Usage
- Credits

### Description
This project uses the MNIST database of handwritten digits for a classification task using the Random Forest Classifier from the scikit-learn library. The aim is to accurately classify the images of handwritten digits from the MNIST database into the respective 10 classes (0-9).

### Installation
To run this project locally, you will need to have the following dependencies installed:

- Python 3.x
- scikit-learn
- numpy
- pandas
- matplotlib (optional for visualizations)
- keras (optional if using the mnist module)

Clone this repository to your local machine and navigate to the project folder.
- $ git clone https://github.com/<your-username>/MNIST-Handwritten-Digits-Classification-with-Random-Forest.git
- $ cd MNIST-Handwritten-Digits-Classification-with-Random-Forest

### Usage
- Create a file named mnist_task.ipynb
- Load the MNIST dataset either by downloading the files or using the mnist module from keras.datasets
- Split the training data into a training and development set with a comment explaining their purpose
- Train a Random Forest Classifier model using the scikit-learn library
- Tune one parameter of the model and explain the choice
- Test the model on the test data and set the value for the chosen parameter
- Print the confusion matrix for the model on the test set
- Report the classes the model struggles with the most
- Report the accuracy, precision, recall, and f1-score for the model
### Credits
This project was created by Harshit Mahida.

If you found any bug or want to contribute to the project, feel free to create a pull request.
