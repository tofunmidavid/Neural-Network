# Neural-Network

# Position Level vs. Salary Prediction using Neural Networks

This project demonstrates how to use a deep learning regression model built with PyTorch to predict employee salaries based on their position level. The model learns the non-linear relationship between experience level and salary, producing smooth, data-driven predictions beyond simple linear regression.
# what is inside
A clean, fully working PyTorch model for regression
Data preprocessing and feature scaling using scikit-learn
Training loop with MSELoss and Adam optimizer
Inference with inverse-transformed predictions
Visual comparison between actual and predicted salaries

# Model Architecture
Input layer → Hidden (128) → Hidden (128) → Output (3)
Activation: ReLU
Optimizer: Adam (lr=0.01)
Loss: Mean Squared Error (MSE)

# 📊 Visualization

The project includes a visualization comparing:
Blue points → actual salary data
Orange curve → model’s predicted regression fit.

# 🛠️ Tools & Libraries

Python 3.x
PyTorch
Matplotlib
NumPy / Pandas
scikit-learn

# 💡 Future Improvements
Hyperparameter tuning (learning rate, hidden size, activation)
Experiment with non-linear activation functions (e.g., LeakyReLU, Tanh)
Integrate interactive plots using Plotly
