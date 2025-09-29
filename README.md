# Flight Data Analysis & Random Walk Metropolis Sampling

## Overview
This project is divided into two main parts:

1. **Random Walk Metropolis Algorithm (MCMC):**  
   Applied a Markov Chain Monte Carlo method to generate samples from a Laplace distribution and analyzed convergence using multiple chains and R-hat diagnostics.  

2. **US Flight Data Analysis (1999–2008):**  
   Analyzed historical airline flight data to explore delays, cancellations, and diversions. Investigated trends over time, the effect of aircraft age, and applied logistic regression to identify key features influencing flight diversions.

---

## Dataset
The project uses the **Airline On-Time Data (1999–2008)**, publicly available through [Harvard Dataverse](https://doi.org/10.7910/DVN/HG7NV7).  
The dataset contains:  
- Departure and arrival times  
- Flight delays and cancellations  
- Aircraft age and distance flown  
- Diversion indicators  

---

## Project Highlights
- **Part 1: Random Walk Metropolis Sampling**  
  - Implemented algorithm to sample from a Laplace distribution.  
  - Generated multiple chains and tested convergence with R-hat values.  

- **Part 2: Flight Data Analysis**  
  - Identified best days and times to minimize delays across years.  
  - Analyzed how aircraft age impacts delay probability.  
  - Applied logistic regression to study features influencing flight diversions.  

---

## Notebooks
- [Part 1: Random Walk Metropolis Sampling](notebooks/Part1_RandomWalkMetropolis.ipynb)  
- [Part 2: Flight Data Analysis](notebooks/Part2_FlightDataAnalysis.ipynb)  

---

## Tools & Libraries
- Python  
- Pandas, NumPy (data manipulation and computation)  
- Matplotlib, Seaborn (data visualization)  
- scikit-learn (logistic regression, train/test split)  

---

## Future Directions
- Extend analysis to post-2008 flight data for updated insights.  
- Incorporate additional predictors such as weather and airport congestion.  
- Apply advanced classification methods (Random Forest, Gradient Boosting) for diversion prediction.  

---

## Report
The full written analysis is available in:  
- [Project Report (PDF)](Data_Science_Report.pdf)  

---

## About
This project was completed as part of the **Programming for Data Science** coursework at the **London School of Economics**.  
It demonstrates statistical sampling, large-scale data analysis, and predictive modeling applied to real-world aviation data.  
