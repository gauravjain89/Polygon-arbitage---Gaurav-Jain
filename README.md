# Polygon Arbitrage Opportunity Detector Bot (Simulation)

This project simulates an arbitrage detector bot for the Polygon blockchain, focusing on WETH/USDC price differences between two decentralized exchanges (DEXs): Uniswap and QuickSwap.

## Features

- Simulates fetching prices from two DEXs using mock/random data.
- Detects arbitrage opportunities based on simulated prices and fixed gas costs.
- Prints estimated profit and recommended trade direction if an opportunity exists.

## How It Works

1. Random prices for WETH/USDC are generated for Uniswap and QuickSwap.
2. Gas cost is set to a fixed value (5 USDC).
3. The bot checks if arbitrage is possible and outputs the results.

## Getting Started

### Prerequisites

- C++ compiler (e.g., g++, clang++)

### Build and Run

```bash
g++ Gauravjain.cpp -o arbitrage-bot
./arbitrage-bot
```

## Code Overview

- `getPriceFromDEX`: Simulates price fetching.
- `checkArbitrage`: Checks for arbitrage and estimates profit.
- `main`: Runs the simulation.

## License

This project is for educational purposes and simulation only.