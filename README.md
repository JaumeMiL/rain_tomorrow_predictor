
# Multilayer Perceptron Model for Predicting Rain 🌧️

This repository contains the implementation of a Multilayer Perceptron (MLP) model to predict whether it will rain tomorrow or not using the "rain data" dataset. This project was created as part of the coursework for the Artificial Intelligence degree at the Universitat Politècnica de Catalunya.

## Authors
- Jaume Mora Ladària
- Marta Nadal Par

## Project Structure 📂
- `MNadal_JMora_Practica1_Notebook.ipynb` - Jupyter notebook with all the code and analysis.
- `rain_data.csv` - Dataset used for the model.

## Setup and Running 🚀

### Installation
Ensure you have Python 3.x installed.

Clone this repository to your local machine:
```bash
git clone https://github.com/JaumeMiL/rain_tomorrow_predictor/
cd rain_tomorrow_predictor
```

Install the necessary Python packages:
```bash
pip install pandas numpy sklearn matplotlib seaborn tensorflow
```

### Running the Notebook
To run the notebook, you can open it using Jupyter Notebook or JupyterLab:
```bash
jupyter notebook MNadal_JMora_Practica1_Notebook.ipynb
```
or
```bash
jupyter lab MNadal_JMora_Practica1_Notebook.ipynb
```

Follow the instructions within the notebook to execute the models.

## Data Analysis 📊
The project starts with an exploratory data analysis (EDA) where the dataset is visualized and statistically analyzed to understand the correlations and distributions of different variables.

## Models
Multiple models were built and iterated upon, starting with a basic logistic regression model and gradually moving to more complex Multilayer Perceptron models. The models were evaluated based on accuracy, precision, and F1-score metrics.

## Best Model 🏆
The best performing model is the final MLP model with one hidden layer of 10 neurons, demonstrating stable and efficient learning without overfitting.

## Conclusion 📝
The project highlights the effectiveness of a simple neural network architecture in predicting weather-related outcomes and provides a robust methodology for handling and analyzing complex datasets.

## Acknowledgements
- Universitat Politècnica de Catalunya. Grau en Intel·ligència Artificial. Xarxes Neuronals i Deep Learning.
