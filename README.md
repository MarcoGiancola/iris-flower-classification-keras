## **Iris Flower Classification with a Keras Neural Network**

This project implements a simple feed‑forward artificial neural network (ANN) built with **Keras** to classify iris flowers into three species: *Setosa*, *Versicolor*, and *Virginica*.  
The model is trained on the classic **Iris dataset**, available at:  
https://gist.github.com/netj/8836201

---

## **Project Overview**

This project demonstrates a complete supervised machine learning workflow:

- Data loading and preprocessing  
- Label encoding (one‑hot)  
- Train/test split  
- Neural network design with Keras  
- Model training and evaluation  
- Confusion matrix and classification report  
- Saving and reloading the trained model  
- Interactive prediction based on user input  

Originally developed as a personal exercise, the project has been rewritten and documented for portfolio purposes.

---

## **Model Architecture**

The neural network is a fully connected feed‑forward model with:

- **Input:** 4 numerical features  
- **Hidden layers:** 3 Dense layers with `tanh` activation  
- **Output:** 3 neurons with `softmax` activation  

Optimizer: **Adam**  
Loss function: **categorical_crossentropy**

---

## **Results**

The model achieves high accuracy on the test set.  
A confusion matrix and a classification report are included to evaluate performance.

---

## **Dataset**

The dataset contains 150 samples of iris flowers, each described by:

- sepal length  
- sepal width  
- petal length  
- petal width  

Target classes:

- Setosa  
- Versicolor  
- Virginica  

Dataset source:  
https://gist.github.com/netj/8836201

---

## **Saving and Loading the Model**

The trained model can be saved as `model1.h5` and reloaded later for inference.

---

## **Interactive Prediction**

The notebook includes a simple interactive section where the user can manually input flower measurements and receive a predicted class.

---

## **Repository Structure**

```
/data
    iris.csv
/notebooks
    iris_classifier.ipynb
model1.h5 (optional)
README.md
```

---

## **Technologies Used**

- Python  
- NumPy  
- Pandas  
- Scikit‑learn  
- TensorFlow / Keras  

---

## **License**

This project is for educational purposes.

