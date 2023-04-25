# ISYE6644-GRP236-OptionPricing
Group 236 Options Pricing Project Repo for Spring'23 ISYE 6644 - Simulations

## Setup
1. Create virtual environment.
   Make sure to use python 3.

```zsh
$ python3 -m venv venv
```

2. Activate virtual environment.
   
```zsh
$ . venv/bin/activate
```

3. Install requirements

```zsh
$ pip install -r requirements.txt
```


## Sections:

The notebooks can be run in order and cover a variety of topics related to simulation of Stock Option Pricing

### Part 1 & 2
Notebook Part_1_and_2 contains simulations of Brownian Motion, Geometric Brownian Motion, European Options (Puts and Calls), and the Greeks . It includes demos and plots of simulating Options and Greeks as functions of a dependent variable using variance reduction with Common Random Numbers (*Jonathan Fine*). Simulation of Asian Options are also included in this notebook(*Emmanuel Isaac*).

### Part 3
Notebook Part_3 contains a library of functions to simulate Geometric Brownian Motion, Geometric Brownian Motion with Antithetic Variance Reduction and incorporates them to price European as well as American Options (Puts and Calls) the analytical way(Black Scholes and Binomial Option Pricing model) and with Monte Carlo simlations(Using Least Squares Monte Carlo). The notebook illustrates the pricing functions by calculating the put and call of a particular strike across various methods of Berkshire Hathaway Stock. The notebook also functions as a playground to test and price an option of the examiners choosing by changing the stock ticker(Available on AlphaVantage website) and the strike price as required.

