# Volatility Surface Plotter

This project allows users to plot the **volatility surface** for options of any publicly traded stock using the Black-Scholes model. The application fetches historical options data via `yfinance`, calculates implied volatility, and displays a 3D interactive surface plot that varies by strike price and time to expiration. The user can input a stock ticker, and the tool will generate the corresponding volatility surface.

## Features

- **Input any Stock Ticker**: Enter any valid stock ticker symbol (e.g., AAPL, TSLA, MSFT) to fetch and visualize its options volatility surface.
- **Interactive 3D Plot**: The plot is generated using `plotly`, allowing for dynamic exploration (rotation, zoom, hover) of the surface.
- **Black-Scholes Formula**: Implied volatilities are calculated based on the Black-Scholes model.
- **Widgets for Interaction**: The program features an input box and button using `ipywidgets` for easy interaction within Jupyter notebooks.
