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
Notebook Part_1_and_2 contains simulations of Brownian Motion, Geometric Bronian Motion, European Options (Puts and Calls), and the Greeks (*Jonathan Fine*) . It includes demos and plots of simulating Options and Greeks as functions of a dependent variable using variance reduction with Common Random Numbers. Asian Options are also included (*Emmanuel Isaac*).
