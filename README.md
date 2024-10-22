
# Predicting Temperature Trends in Tahoe 

**DATASCI 207 - Summer 2024**  
Team Members: Sid, Joan, Teja, Alex  
Instructor: Prof. John Santerre

## Project Overview 

This project aims to predict **average temperature trends** in Tahoe using historical climate data from the *National Centers for Environmental Information (NCEI)* and deforestation trends from the *Global Forest Watch*. Our goal is to leverage **Machine Learning (ML)** techniques to improve **public safety**, support **environmental planning**, and enhance decision-making for economic and recreational sectors.

## Data Sources 
- **NCEI Global Climate Database**: Meteorological data such as minimum, maximum, and average temperatures.
- **Global Forest Watch Dataset**: Annual deforestation data used as a feature for climate correlation.

## Key ML Models & Techniques 🛠

### Baseline Models
1. **Linear Regression**
2. **Neural Network Regression**
3. **XGBoost Regressor**

### Time Series Models
1. **ARIMA**: Utilized for analyzing temporal trends in temperature.
2. **LSTM (Long Short Term Memory)**: A recurrent neural network model effective for capturing long-term and short-term trends in climate data.

### Performance Results
| **Model**         | **RMSE**   |
|-------------------|------------|
| Linear Regression | 4.748      |
| Neural Network    | 3.992      |
| XGBoost           | 3.059      |
| ARIMA             | 1.720      |
| LSTM              | **1.536**  |

The LSTM model outperformed all others, providing the most accurate temperature predictions by learning both seasonal and temporal patterns.

## Challenges & Limitations 
- **Limited Data**: We faced limitations in the size of the NCEI dataset and only had annual forest cover loss data.
- **Complexity of Weather Patterns**: Predicting sharp temperature peaks and troughs proved difficult due to the complexity of weather dynamics.
- **Geographical Scope**: Our models are currently focused solely on the Tahoe region.

## Future Work 
- **Expand Data Sources**: Incorporate additional features like precipitation and solar radiation.
- **Broaden Geographic Scope**: Extend model predictions to other regions.
- **Collaborate with Experts**: Work with climatologists to enhance model performance and address the complexity of predictions.

## License ⚖️
This project is licensed under the MIT License.
