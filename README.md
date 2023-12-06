# COVID-19 Vaccine Interactive Analysis and Visualisation Dashboard

A Web App to interact and visualize the analysis of COVID-19 vaccinations across the world. 

App is deployed in Heroku, click the link to access it : [Open in Heroku](Provide your site URL here) 

## Summary

The goal of the COVID-19 vaccine is to acquire immunity against the virus that causes coronavirus disease 2019 (COVID-19), which is caused by the severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2). The way the COVID-19 vaccines function is by exposing the body to a weakened or dormant strain of the SARS-CoV-2 virus. If the body is exposed to the virus again, this aids in the development of antibodies by the immune.

In this notebook, I am going to explore the dataset from world data. Name:- the complete Our World in Data COVID-19 dataset. this dataset includes all vaccinations or everything about COVID-19 and COVID-19 vaccines.

## Data

I gathered my data from Our World in Data.
Refer below : 
https://github.com/owid/covid-19-data/blob/master/public/data/owid-covid-data.csv

The data here gets updated every 24 hours from the official sources. I accessed these files from the above-given sources.

## Pre-requisites

The project was developed using Python 3 (ipykernel) with the following packages.
- Pandas
- Numpy
- matplotlib
- plotly
- ipywidgets
- folium
- voila
- voila-material

Installation with pip:

```bash
pip install -r requirements.txt
```

## Getting Started
Open the terminal in your machine and run the following command to access the web application in your local host.
```bash
voila ./notebooks/DBoard.ipynb --template=material
```

or,
```bash
voila DBoard.ipynb --debug
```

## Files
- notebooks/Vaccine.ipynb : Jupyter Notebook with all the analysis done on the owid-covid-data dataset.
- notebooks/DBoard.ipynb : Jupyter Notebook with all the necessary analysis on owid-covid-data dataset. (Both the notebooks are the same except this one contains the codes which are explicitly required for Dashboard only).
- requirements.txt: pre-requisite libraries for the project.
- Procfile: To trigger the app in Heroku.
