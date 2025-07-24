# FinSearch
# Options and Option Pricing Models 📈

This repository contains our project code from **FinSearch**, focused on the implementation and backtesting of fundamental option pricing models. As a collaborative effort, this project explores the practical application of financial mathematics using modern Python libraries.

---

## Overview

Our primary goal was to program three widely-used option pricing models from scratch to develop a deep, practical understanding of their mechanics. These models were then backtested against historical market data from the **Nifty50 index** to evaluate their accuracy and performance.

The project covers:
* The structure and types of options (Calls, Puts).
* Key option metrics (Greeks, premium, etc.).
* Implementation of pricing models for European options.

---

## Models Implemented

We programmed the following models using **NumPy** and **Pandas** for efficient data handling and numerical computation.

### 1. Black-Scholes Model
A mathematical model that provides a theoretical price for European-style options. It's based on a formula that considers the underlying stock price, strike price, time to expiration, risk-free rate, and volatility.

### 2. Binomial Tree Model
A discrete-time numerical method that maps out the possible paths the underlying asset's price could take over the option's life. It's more flexible than Black-Scholes and can handle a wider variety of options.

### 3. Monte Carlo Simulation
A computational model that uses random sampling to simulate thousands of potential price paths for the underlying asset. The final option price is determined by averaging the discounted payoffs from these simulations.

---

## Technology Stack & Dataset

* **Language:** Python
* **Libraries:** NumPy, Pandas, Matplotlib
* **Dataset:** Historical options data for the **Nifty50 index** was used for backtesting.

---

## Getting Started

To get a local copy up and running, follow these simple steps.

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/your-club/your-repo-name.git](https://github.com/your-club/your-repo-name.git)
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd your-repo-name
    ```
3.  **Install the required packages:**
    ```sh
    pip install -r requirements.txt
    ```
4.  **Run the main script:**
    ```sh
    python main.py
    ```


