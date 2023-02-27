---
layout: single
title:  "Trading system"
categories: Performance Measures
tag: [SharpRatio, ForwardAnalysis, system, AverageP, trading, Overfitting, measures, performance]
use_math: true
toc: true
toc_sticky: true
toc_label: 목차
---
## Maximum Drawdown (MDD)
The Maximum Drawdown (MDD) is a measure of the largest peak-to-trough decline in a trading system. It is calculated as the difference between the highest peak and the lowest trough of the system. The formula for MDD is:

$$ MDD = \frac{V_{peak} - V_{trough}}{V_{peak}} $$

where $V_{peak}$ is the highest peak and $V_{trough}$ is the lowest trough of the system.

## Maximum Favorable Excursion (MFE)
The Maximum Favorable Excursion (MFE) is a measure of the maximum amount of profit that can be achieved in a trading system. It is calculated as the difference between the highest peak and the highest point of the system. The formula for MFE is:

$$ MFE = \frac{V_{peak} - V_{high}}{V_{peak}} $$

where $V_{peak}$ is the highest peak and $V_{high}$ is the highest point of the system.

## Maximum Adverse Excursion (MAE)
The Maximum Adverse Excursion (MAE) is a measure of the maximum amount of loss that can be incurred in a trading system. It is calculated as the difference between the lowest trough and the lowest point of the system. The formula for MAE is:

$$ MAE = \frac{V_{trough} - V_{low}}{V_{trough}} $$

where $V_{trough}$ is the lowest trough and $V_{low}$ is the lowest point of the system.

## Sharp Ratio
The Sharp Ratio is a measure of the risk-adjusted return of a trading system. It is calculated as the ratio of the average return of the system to the standard deviation of the returns. The formula for Sharp Ratio is:

$$ Sharp Ratio = \frac{Average Return}{Standard Deviation} $$

## Profit and Loss (P&L)
The Profit and Loss (P&L) is a measure of the total profit or loss of a trading system. It is calculated as the difference between the total profits and total losses of the system. The formula for (P&L) is:

$$ P&L = Total Profits - Total Losses $$

## Average Profit/Loss (P/L)
The Average Profit/Loss (P/L) is a measure of the average profit or loss of a trading system. It is calculated as the average of the total profits and total losses of the system. The formula for Average P/L is:

$$ Average P/L = \frac{Total Profits + Total Losses}{2} $$

## Forward Analysis
Forward Analysis is a measure of the accuracy of a trading system's predictions. It is calculated as the ratio of the number of correct predictions to the total number of predictions. The formula for Forward Analysis is:

$$ Forward Analysis = \frac{Number of Correct Predictions}{Total Number of Predictions} $$

## Overfitting
Overfitting is a measure of the ability of a trading system to generalize from past data. It is calculated as the difference between the performance of the system on the training data and the performance of the system on the test data. The formula for Overfitting is:

$$ Overfitting = Performance on Training Data - Performance on Test Data $$

Next, we will use Kakao stock data for 2022 to calculate each of these performance indicators. With the help of Python code, you can easily calculate the value of each indicator and use it to measure the performance of your trading system. #trading #system #performance #measures #MDD #MFE #MAE #SharpRatio #P&L #AverageP/L #ForwardAnalysis #Overfitting
