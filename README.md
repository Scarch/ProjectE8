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
- `analysing_preparing_capitalBikeshareData.ipynb`
- `exploring_data.ipynb`
- `kaggle_model.ipynb`
- `E8_report.pdf`

## Replicating what we've done

## TODO

- [ ] Organize files into folders
- [ ] Make README file more informative
