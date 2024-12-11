# KAGGLE-BIKE-SHARING-DEMAND (Project E8)

Analysing and predicting bike rental demand based on weather, date and time.

## Team members

- Sten-Egert Märtson
- Kaur Kivilaan

## Relevant links

- https://www.kaggle.com/competitions/bike-sharing-demand
- https://capitalbikeshare.com/system-data

## Goals and motivation

Both of us consider the bike sharing topic to be interesting and relevant so picking it as a target for analysis felt natural. With this project we essentially aimed to analyse data pertaining to the Washington D.C. based bike sharing company. Since they did a [collaborative competition](https://www.kaggle.com/competitions/bike-sharing-demand) with Kaggle as well, we had a solid base for implementing data science methods we've learned.

To be more specific, we wished to attain a sufficiently good model (RMSLE score below 0.4) for predicting how many bikes are rented in an hour if we're given information about said hour (weather, date, time and societal factors such as the hour falling on a day that is a holiday, working day or weekend). We also hoped to use the abundant amounts of [data provided by Capital Bikeshare](https://capitalbikeshare.com/system-data) on their homepage to make broader conclusions on how various features (such as the features in the Kaggle competition) influence bike rental demand with the help of knowledge gained from participating in the Kaggle competition.

The insight gained from this project could hopefully help optimize bike availability during peak times and plan maintenance during periods of low demand, improving overall system efficiency and user satisfaction.

## Project guide

- The folder `capitalBikeshareData` contains the public [system data zip files provided by Capital Bikeshare](https://capitalbikeshare.com/system-data)
- All of the files provided by the Kaggle [Bike Sharing Demand](https://www.kaggle.com/competitions/bike-sharing-demand/data) competition reside in the folder `kaggleData`
- `./submissions` folder - *almost* all our submissions to the Kaggle competition (some submissions were overwritten by accident)
- `./dataVisualisation` folder - data visualisation graphics that were exported for possible addition to the poster
- `analysing_preparing_capitalBikeshareData.ipynb` - a documented Jupyter Notebook file which covers the data preparation and analysis steps taken regarding the Capital Bikeshare system data
- `training_ml_model_on_capital_bikeshare_data.ipynb` - a documented Jupyter Notebook file that shows the process of creating three machine learning models and training them on the `bikesRentedPerHourCombinedData.csv` file
- `best_kaggle_models` - a documneted Jupyter Notebook file that shows the process of creating the best versions (that we found) of machinel learning models that we tested and used in the Kaggle competition
- `exploring_data.ipynb` - the first steps for analysing the data. The findings were reported in the "*Exploring data*" section of `E8_report.pdf`.
- `kaggle_model.ipynb` - Jupyter Notebook file where we tested different machine learning models for the Kaggle competition
- `E8_report.pdf` - report for the tasks in homework 10

## Replicating what we've done

If one wishes to see what conclusions we've reached and how we reached them, they can take a look at our Jupyter Notebook files (ending with `.ipynb`), which cover our actions step by step.

## TODO

- [ ] Organize files into folders
- [ ] Make README file more informative
