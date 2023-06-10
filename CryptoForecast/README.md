# CryptoForecast Repository

This repository, named "CryptoForecast," is designed for forecasting digital currencies using artificial intelligence algorithms. It includes four notebooks:

1. `CryptoLSTM.ipynb`: This notebook utilizes the LSTM (Long Short-Term Memory) layer for cryptocurrency prediction. It retrieves data from the following website: [cryptocompare](https://min-api.cryptocompare.com/data/histoday?fsym=ETH&tsym=CAD&limit=2000).

2. `CryptoTradingLSTM.ipynb`: In this notebook, LSTM is employed for Bitcoin prediction specifically, with a focus on trading strategies.

3. `CryptoCurrencyMultiState.ipynb`: This notebook employs a multi-state network with LSTM for Bitcoin prediction.

4. `CryptoCurrencyMultiStateGRU.ipynb`: This notebook utilizes a multi-state network with GRU (Gated Recurrent Unit) for Bitcoin prediction.

Please refer to the respective notebooks for detailed implementation and usage instructions.

## Usage

To use this repository, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/MohamadsalehMoradpoor/ForecastAI.git
   ```

2. Navigate to the project directory:

   ```bash
   cd CryptoForecast
   ```

3. Open the desired notebook, such as `CryptoLSTM.ipynb`, `CryptoTradingLSTM.ipynb`, `CryptoCurrencyMultiState.ipynb`, or `CryptoCurrencyMultiStateGRU.ipynb`, using Jupyter Notebook or any compatible environment.

4. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

```css
It's recommended to set up a virtual environment and install the necessary packages using a package manager like pip or conda.
```

5. Execute the notebook cells in order to perform cryptocurrency forecasting.

## Contributions

Contributions to this repository are welcome. If you wish to contribute, please fork the repository, make your changes, and submit a pull request.