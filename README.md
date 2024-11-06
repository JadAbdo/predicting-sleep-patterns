# predicting-sleep-patterns
This project uses a simple feed-forward neural network to predict the sleep duration of university students based on various sleep-related factors. The model is trained using a dataset that contains information on student age, sleep quality, cafeine intake, and other similar features.

# Dataset
The dataset used in this project was exported from kaggle.com and includes the following features:

- Age (of the student)
- University_Year (year of study of the student)
- Study_Hours (number of hours the student spends studying)
- Screen_Time (time the student spends on their screen)
- Caffeine_Intake (amount of caffeine consumed by the student)
- Physical_Activity (a measure of the student's physical activity)

The target variable is Sleep Duration, which is the output that the neural network predicts.

# Model
The model is a simple feed-forward neural network with:

- Input Layer: 6 features
- Hidden Layer 1: 80 neurons
- Hidden Layer 2: 50 neurons
- Output Layer: A scalar value representing the predicted sleep duration
- ReLU activation is applied to the hidden layers, and Mean Squared Error (MSE) loss is used to train the model.

# Requirements
To run the project, you'll need the following libraries:

- torch (PyTorch)
- pandas
- scikit-learn

# Evaluation
The model's performance is evaluated using the absolute percentage difference between the predicted and true sleep durations. Lower percentage differences indicate better model accuracy.
