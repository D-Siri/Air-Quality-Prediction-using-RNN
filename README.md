# Air Quality Prediction using RNN

## Project Overview

This project focuses on predicting air quality using a Simple Recurrent Neural Network (RNN) model. The dataset contains various air quality measurements including pollutants and environmental factors.

## Contents

1. Data Loading and Preprocessing
2. Exploratory Data Analysis
3. RNN Model Implementation
4. Model Training and Evaluation
5. Results Visualization

## Requirements

- Python 3.x
- TensorFlow
- Keras
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

## Usage

1. Ensure all required libraries are installed.
2. Run the Jupyter notebook.
3. Follow the code cells sequentially to reproduce the analysis and results.

## Model Architecture

- SimpleRNN with 64 units
- Input shape: (10, 32)
- Dense layer with sigmoid activation for binary classification

## Key Features

- Time series data preprocessing for RNN input
- Implementation of SimpleRNN for sequence prediction
- Comprehensive model evaluation using various metrics

## Results

- R2 Score: 0.9097



## License
MIT License

Copyright (c) [2024] [Siri Duggineni]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
