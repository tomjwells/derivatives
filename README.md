# Derivatives Valuation Model

This toolkit provides a comprehensive suite of tools to price derivatives, specifically European options. The toolkit uses Monte Carlo simulations and the risk-neutral pricing method to accurately estimate option prices.

## Usage

See the file `run_examples.py` for useage.

## Convergence

## Features

- **Monte Carlo Simulations**: This method involves running a large number of simulations to model the price of an underlying asset, taking into account factors such as volatility and time to expiration. This is particularly useful for pricing American options, which can be exercised at any time before expiration.

- **Risk-Neutral Pricing**: This is a method used to price derivatives when the risk-free rate is known. It assumes that the expected return of the underlying asset is the risk-free rate.

- **European Options**: The toolkit can price both European options, which can only be exercised at expiration

## How to Use

To use this toolkit, you will need to provide the necessary parameters for the option you want to price, such as the strike price, the risk-free rate, the volatility of the underlying asset, and the time to expiration. The toolkit will then use these parameters to run the Monte Carlo simulations and/or calculate the risk-neutral price.

## Requirements

This toolkit is written in Python and requires the following libraries:

- numpy
- scipy
- pandas

## Installation

You can install the required libraries with pip:

```bash
pip install numpy scipy pandas
```

Then, you can clone this repository to your local machine:

## Examples
Please refer to the examples directory for examples on how to use this toolkit to price options.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
If you have any questions or suggestions, please feel free to get in touch.