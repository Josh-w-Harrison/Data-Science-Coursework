# Data Science Coursework
 
My solutions to the University of Cambridge Engineering Part IB Data Science coursework, written in Python with NumPy, pandas and Matplotlib.
 
The notebooks in the top-level folder are the course's teaching notebooks. They work through regression and seasonal modelling on NOAA atmospheric CO₂ data. My own work is in the `Exercises/` folder.
 
## Exercises
 
### Exercise 1: Polynomial regression
 
- Implemented least-squares polynomial regression from the design matrix.
- Fitted models of order 2 to 4 to a synthetic dataset and compared them using SSE and R².
- Checked the residuals of the chosen model against a Gaussian with matching variance.
### Exercise 2: Exponential growth of COVID hospital admissions
 
- Fitted an exponential model to UK hospital admissions over three weeks of the Omicron wave (late December 2021), as a linear regression on log admissions.
- Used the fitted growth constant to estimate the weekly growth rate in admissions.
### Exercise 3: Trend and seasonal modelling of TfL ridership
 
- Fitted a linear trend to 19 years of average daily London Underground ridership (2000 to 2019).
- Computed the periodogram of the residuals to identify the dominant periodic components.
- Fitted sinusoids at those frequencies to the residuals and compared the combined trend plus seasonal model against the linear fit using MSE and R².
All models are fitted and evaluated on the same data. The optional model selection exercise, which uses a separate training and test split, was not attempted.
 
## Tools
 
Python, NumPy, pandas, Matplotlib, Jupyter
 
