# WorldQuant Brain Quantitative Analysis Challenge - Inter IIT Tech Meet 12.0, IIT Madras
## Table of Contents

- [Overview](#overview)
- [Alpha Strategies](#alpha-strategies)
  - [Tail Risk Strategy](#tail-risk-strategy)
  - [Size Effect Strategy](#size-effect-strategy)
  - [Call Option Implied Volatility Strategy](#call-option-implied-volatility-strategy)
- [Backtesting and Validation](#backtesting-and-validation)
  - [Out-of-Sample Testing](#out-of-sample-testing)
- [Results](#results)

## Overview

This repository contains the presentation and detailed analysis of three unique alphas developed for the WorldQuant Brain Quantitative Analysis Challenge held during the Inter IIT Tech Meet 12.0 at IIT Madras in December 2024. The alphas were backtested on the US Equity Markets and focused on distinct hypotheses including tail risk, the 'Size Effect' in smaller firms, and call option implied volatility. The strategies were validated using out-of-sample testing (2021-2023), demonstrating their predictive accuracy and market performance.



## Alpha Strategies

### Tail Risk Strategy

This strategy focuses on identifying and mitigating tail risks in the market. Tail risk refers to the risk of an asset or portfolio of assets moving more than three standard deviations from its current price, representing extreme changes in the value of an investment.

### Size Effect Strategy

The Size Effect Strategy leverages the 'Size Effect' hypothesis, which suggests that smaller firms tend to outperform larger firms in terms of stock returns. This alpha was designed to exploit the inefficiencies in the pricing of smaller firms' stocks.

### Call Option Implied Volatility Strategy

This strategy utilizes the implied volatility derived from call options. Implied volatility is a measure of the market's expectation of volatility and is used to gauge the future volatility of the underlying stock. The strategy aims to capture the predictive power of implied volatility in forecasting stock price movements.

## Backtesting and Validation

### In-Sample Testing Results

1.Tail Risk Strategy

<img width="690" alt="Screenshot 2024-06-20 at 17 48 33" src="https://github.com/daksharora01/Inter-IIT-WorldQuant/assets/121610907/ac85e89b-09c3-4d2c-9cc3-0366a2dd5b5f">

2.Size Effect Strategy

<img width="637" alt="Screenshot 2024-06-20 at 17 48 52" src="https://github.com/daksharora01/Inter-IIT-WorldQuant/assets/121610907/deae6cdb-748c-4ec6-8b3d-bb6aeac0dd7d">

3.Call Option Implied Volatility Strategy

<img width="631" alt="Screenshot 2024-06-20 at 17 49 08" src="https://github.com/daksharora01/Inter-IIT-WorldQuant/assets/121610907/5b561ed8-7415-44e4-b9a0-1379593a7a9a">


### Out-of-Sample Testing

The strategies were validated using out-of-sample testing, covering the period from 2021 to 2023. Out-of-sample testing is a method of testing the performance of a trading strategy on data that was not used during the development of the strategy, ensuring the robustness and predictive accuracy of the alphas.

## Results

The backtesting and out-of-sample testing results demonstrated that the developed alphas had strong predictive accuracy and market performance. Detailed results and analysis can be found in the presentation included in this repository.

