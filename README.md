# Neural Activation Functions Visualizer

A compact Python notebook that implements and visualizes common neural network activation functions used in deep learning. The project plots the Step, Sigmoid, Tanh, and ReLU functions with NumPy and Matplotlib to show how each function transforms input values.

## Project Overview

This project was completed for an introductory deep learning class activity. It demonstrates how several foundational activation functions behave across a continuous input range from negative to positive values.

Activation functions are a core part of neural networks because they determine how neuron outputs are transformed before being passed to later layers. This notebook focuses on clear mathematical implementation and visual comparison.

## Features

- Implements common activation functions in Python
- Uses NumPy for vectorized numerical computation
- Uses Matplotlib to generate labeled function plots
- Visualizes the differences between threshold, sigmoid shaped, zero centered, and piecewise linear activation functions
- Includes both the original Jupyter Notebook and an exported PDF version of the completed activity

## Activation Functions Included

### Step Function

The step function outputs `0` for negative inputs and `1` for nonnegative inputs. It represents a simple binary threshold function.

### Sigmoid Function

The sigmoid function maps inputs to values between `0` and `1`. It produces a smooth S shaped curve and is commonly used when outputs need to be interpreted like probabilities.

### Tanh Function

The hyperbolic tangent function maps inputs to values between `-1` and `1`. It is similar to sigmoid, but it is zero centered, which can make it more useful in some neural network layers.

### ReLU Function

The Rectified Linear Unit outputs `0` for negative inputs and returns the input value for positive inputs. ReLU is widely used in deep learning because it is simple, efficient, and effective for many neural network architectures.

## Technologies Used

- Python
- NumPy
- Matplotlib
- Jupyter Notebook
- Google Colab compatible notebook format

## Repository Structure

```text
.
├── Jason_Stys,_Class_Activity_1,_CS_478_01.ipynb
├── Jason Stys, CS 478-01, Class Activity 1.pdf
└── README.md
```

## How to Run

Clone the repository.

```bash
git clone https://github.com/your-username/neural-activation-functions-visualizer.git
cd neural-activation-functions-visualizer
```

Install the required Python packages.

```bash
pip install numpy matplotlib notebook
```

Launch Jupyter Notebook.

```bash
jupyter notebook
```

Open the notebook file and run all cells.

## Example Output

The notebook generates plots for each activation function:

- Step Function
- Sigmoid Function
- Tanh
- ReLU

Each plot includes a title, labeled x axis, labeled output axis, and gridlines for readability.

## Skills Demonstrated

- Python programming
- Mathematical function implementation
- Vectorized computation with NumPy
- Data visualization with Matplotlib
- Jupyter Notebook workflow
- Introductory deep learning concepts

## Possible Future Improvements

- Add derivative plots for each activation function
- Add Leaky ReLU, ELU, GELU, Softplus, and SiLU
- Create a single comparison chart with all activation functions
- Add explanations of where each activation function is commonly used in neural networks
- Convert the notebook into a small interactive visualization app
