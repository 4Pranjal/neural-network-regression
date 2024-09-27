# Simple Feedforward Neural Network for Regression

This repository contains code that implements a simple feedforward neural network for regression using manually calculated derivatives for backpropagation. The neural network predicts the 'lpa' (placement score) based on input features 'cgpa' and 'profile_score'.

## Prerequisites

- Python 3.x
- NumPy
- Pandas

## Code Explanation

1. `import` statements: Import the necessary libraries, including NumPy and Pandas.

2. Creating the DataFrame: A DataFrame named `df` is created with input features 'cgpa', 'profile_score', and the target variable 'lpa'.

3. `initialize_parameters` function: This function initializes neural network parameters (weights and biases) using random values.

4. `linear_forward` function: This function performs the linear forward propagation step for a single layer.

5. `L_layer_forward` function: This function performs the forward propagation through all layers of the neural network.

6. `update_parameters` function: This function updates the parameters using backpropagation.

7. Training the Neural Network: The code initializes parameters and performs training epochs. In each epoch, it iterates through the dataset, calculates predictions, updates parameters, and computes the loss.

8. Output: The learned parameters are printed after training.

## Usage

1. Install the required libraries using `pip install numpy pandas`.

2. Run the script using `python neural_network_regression.py`.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please create an issue or pull request in this repository.

## License

This project is licensed under the [MIT License](LICENSE).

---
## Credits

This repository is maintained by 4Pranjal. Feel free to use and modify the code for educational and research purposes.

For any questions or suggestions, you can contact me through my GitHub profile: [@4Pranjal](https://github.com/4Pranjal).

Made with ❤️ by [Pranjal Jain](https://github.com/4Pranjal)


