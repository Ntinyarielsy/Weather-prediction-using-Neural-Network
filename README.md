# Project – COSC 6339 
## School of Engineering & Computer Sciences A & M University at Corpus Christ
## Objective: Build a system to predicate the weather

- project summary.
- Installation and set ups.


### Project summary
This project focuses on the development of a weather prediction system using a feedforward neural network, leveraging machine learning techniques to classify weather conditions into two categories: rain or no rain tomorrow. The dataset, comprising 145,460 rows with diverse features, necessitates meticulous preprocessing. The neural network architecture involves an input layer with Rectified Linear Unit (ReLU) activation, two hidden layers, and an output layer using a sigmoid activation function. The model is trained and evaluated based on a binary crossentropy loss function, achieving a test accuracy of approximately 85%. Overall, the project provides insights into the challenges and successes of implementing a neural network-based weather prediction system.

### Set up and running cde 

Create a python environment 
```
python -m venv dts_nn
```
Run the following code to activate the virtaual environment
```
 source dts_nn/Scripts/activate

```
Install the required packages and libraries
```
pip instal -r requirement.txt

```

Note:
- When you install e.g pandas it come with other libraries like numpy.

Other specification I worked with
- python 3.11
- VSCODE editor 1.82.2
- windows 10
- terminal: Gitbash


Open `weather_predict.ipynb` notebook and run it on the activated virtual environment