![GMIT_Logo.png](GMIT-logo.png)

# ProgDA_Project_20

## Author: Shane Rylands

### G00387904@gmit.ie

This repository contains my submission for Programming of Data Analytics 2020 project. My project is: The Correlation between Obesity and Severity of Covid-19. I have tried to establish a correlation between an individuals Body Mass Index and serverity of Covid-19 symptoms they experience. My investigation did indeed show a strong correlation between the two, which I could then use to make predictions about Covid-19 symptoms based on an indiviuals BMI.

The inspiration for this project came from the following studies;

- https://www.drugtargetreview.com/article/77332/predicting-covid-19-susceptibility-and-severity/#:~:text=Known%20risk%20factors%20for%20severe,older%20age%20and%20male%20sex.

- https://hselibrary.ie/what-is-the-risk-of-a-person-with-obesity-contracting-covid-19-compared-to-someone-without-obesity-what-is-the-risk-of-a-person-with-obesity-developing-severe-illness-from-covid-19-how-is-severe-ill/#Rottoli

- https://www.accessscience.com/content/the-relationship-between-obesity-and-covid-19/BR1002201


***

## <u>Problem statement<u>

For this project you must create a data set by simulating a real-world phenomenon of your choosing. You may pick any phenomenon you wish – you might pick one that is of interest to you in your personal or professional life. Then, rather than collect data related to the phenomenon, you should model and synthesise such data using Python.
We suggest you use the `numpy.random` package for this purpose. Specifically, in this project you should:

- Choose a real-world phenomenon that can be measured and for which you could collect at least one-hundred data points across at least four different variables.
- Investigate the types of variables involved, their likely distributions, and their relationships with each other.
- Synthesise/simulate a data set as closely matching their properties as possible.
- Detail your research and implement the simulation in a Jupyter notebook – the data set itself can simply be displayed in an output cell within the notebook.

***

To run this jupyter notebook file you will need to install Python, ideally through th Anaconda distribution. Then you will need to download this repository to your local device. To open the jupyter notebook from your device, please navigate to the folder containing the notebook in your your command line interface and then type: 

`jupyter notebook`

## <u>Conclusion<u>
  
I am happy with how the project turned out, but there are a number of things I was not able to do:
- I wanted to assign a UUID to each individual in the datset and then set that UUID as the index. My inspiration for that came from this:
https://towardsdatascience.com/generating-product-usage-data-from-scratch-with-pandas-319487590c6d
- I was also unsuccessful with changing the index starting point from 0 to 1. When I did the plotting would no longer work.
https://stackoverflow.com/questions/20167930/start-index-at-1-for-pandas-dataframe
- My Predict function does not work properly and could not figure out why.
- I was unable to apply preprocessing to my dataset so I could not include sex as an input for KNN.
- I was unable to establish a r2 score.
