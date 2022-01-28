# Financial_Planning_Tools

---
![5-4-monte-carlo-line-plot](https://user-images.githubusercontent.com/95719899/151509413-2ce13cf5-5515-4c18-aab0-605dac104b3f.png)


For the purpose of this exercise, I’ve decided to start a fintech consulting firm that focuses on projects to benefit local communities. I just won my first contract with a large credit union. The project entails building a tool to help credit union members evaluate their financial health. 

Specifically, the credit union board wants the members to be able to do two things:

First, they should be able to assess their monthly budgets. 
Second, they should be able to forecast a reasonably effective retirement plan based on their current holdings of cryptocurrencies, stocks, and bonds. 

The chief technology officer (CTO) of the credit union wants me to develop a prototype application to present at its next assembly.

---

## Technologies

**A Python 3.9.7 (ipykernal) in JupyterLab** was used to write this notebook.


Additional Python libraries are imported into the start of the app: 

<img width="341" alt="Screenshot 2022-01-28 003546" src="https://user-images.githubusercontent.com/95719899/151506131-791f8049-f3ca-4f02-a030-424c0901f12a.png">



---

## Installation Guide

To use the app, from the Github repository, download:
- **financial_planning_tools.ipynb** Jupyter file 
- **Images** folder that contains example images
- **MCForecastTools.py** toolbox that rus Monte Carlo Simulations
- **SAMPLE.env** file to store Alpaca API keys

Use either Terminal or Git Bash to run the app in a conda dev environment. 
To enter a conda dev environment, type
'conda activate dev'

To run the app, navigate to the root directory, which contains all the files adjacent to one another, and then type
'jupyter lab'


To use this tool, you will need to have a free account and a set of API keys with https://alpaca.markets/


You will input your API keys into the **SAMPLE.env** file and save it as **.env**

<img width="878" alt="Screenshot 2022-01-28 003236" src="https://user-images.githubusercontent.com/95719899/151507500-f5ca164a-2b92-4287-bbfd-2354f71ff86a.png">

---

## Usage

As you run through the tools, observe how I created two financial analysis tools by using a single Jupyter notebook:



1. **A financial planner for emergencies.** The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.


<img width="817" alt="Screenshot 2022-01-28 005628" src="https://user-images.githubusercontent.com/95719899/151508853-e2099cbf-02e9-4853-b73c-7a0d8a74c46b.png">


2. **A financial planner for retirement.** This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

I’ll use the information from the Monte Carlo simulation to answer questions about the portfolio in your Jupyter notebook.


<img width="725" alt="Screenshot 2022-01-28 003344" src="https://user-images.githubusercontent.com/95719899/151508982-5d038efc-f5da-400a-8a64-fe49f3e497d7.png">


<img width="505" alt="Screenshot 2022-01-28 003441" src="https://user-images.githubusercontent.com/95719899/151509005-2e0c6e13-a58b-4f0a-993b-0300825804e8.png">

---

## Contributors

This exercise was based on a challenge problem from UC Berekely Fintech Bootcamp Module 5, accessed on 2022.01.28. 

For any questions, please reach out to me on [LinkedIn](https://www.linkedin.com/in/lari-rupp-5baa49153/)

---

## License

Creative Commons Zero
