# Using Monte Carlo simulations to account for uncertainty in Economic Evaluation of Energy Investments 

## Introduction

Projects in the energy industry are capital intensive. For example, a scale onshore wind turbine will have capital costs of approximately 1.5 million pounds per MW plus connection to grid and other capital costs. Because of the size of the investments and the need to establish their profitability, it is neccesary to undertake economic valuation of the investments to aid firms in deciding weather to invest or not in energy projects. 

The most common approach for the economic valuation of projects in the energy industry entails capital budgeting techniques based on Discounted Cash Flow Analysis (DCF). There is one shortcoming of DCF analysis: it is based on the assumption that the behaviour of the variables involved is fixed. Howevever, energy projects face several sources of uncertainty, meaning some variables exhibit a random behaviour. 

Monte Carlo simulation (MC) is a useful method to model the probability of different outcomes due to the intervention of random variables. In other words, MC can enhance DCF by accounting for uncertainty in the variables that are part of the energy investment. 

## Objective of this notebook

In this notebook I show how to do Monte Carlo simulations to assess the profitability of an investment in energy generation capacity using Python. Two broad objectives are achieved with the notebook:

1. Showcase the essence of economic valuation in energy investments 
2. Develop a python tutorial for doing basic Discounted Cash Flow analysis and Monte Carlo simulations. 

**Disclaimer:** by no means this notebook shows an exhaustive treatment of capital budgeting techniques and Monte Carlo simulations. It only strives to showcase the basic notions required to undertake economic valuation initiatives and presents a practical tutorial on how to use Python for such purposes. The data and business settings are entirely made up; the models are highly simplified. The python coding is not the only way to do this analysis. I encourage you to try different ways. That is the beauty of data analysis.  
