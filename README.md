# Bank's points of interest in Guayaquil

I have written a blog post for this project, you can have a look at it [here](https://medium.com/@restevesd/mejor-ubicaci%C3%B3n-para-puntos-de-atenci%C3%B3n-entidades-financiera-67887128e1dd)

<img src='./visualizations/airbnb_indoor.jpg'>

This repo contains analysis of point of interest in Guayaquil from a bank institution<br>
Analysis follows ***`CRISP-DM`*** process!<br>

This data is scrap from google map.<br>

`Steps in CRISP-DM process:`
- Business Understanding
- Data Understanding 
- Data Preparation 
- Modelling
- Evaluation
- Setting out (information to stakeholder)

This repo contains all of the above mentioned steps in `airbnb-analysis.ipynb`. 

## Table of contents

- [Installation](#installation)
- [File descriptions](#file-descriptions)
- [Motivation](#motivation)
- [Results](#results)
- [Creator](#creator)
- [Thanks](#thanks)


## Installation

In order to be able to execute your own python statements follow this command to install all requirments:<br>
- `pip install -r requirements.txt`

Two quick start options are available:
- [Download the latest release.](https://github.com/s-nilesh/AirBnB-Data-Analysis/archive/master.zip)
- Clone the repo: `git clone https://github.com/s-nilesh/AirBnB-Data-Analysis.git`


## File descriptions

Within the download you'll find the following directories and files.

```text
Udacity/
+-- udacity.ipynb
+-- datos.csv
+-- README.md
+-- visualizations
    +-- Average price for each accommodates type.png
    +-- average price for month.png
    +-- average price for neighbourhood.png
    +-- calendar_percantage_of_MissingValues.png
    +-- feature importances.png
    +-- listings_percentage_of_MissingValues.png
    +-- number of available listings.png
    +-- Number of listings for each accommodates type.png
    +-- number of listings not available.png
    +-- Number of listings registered each month.png
    +-- number_of_reviews_overtime.png
    +-- occupancy rate over time.png
    +-- Price_distrubution.png
    +-- Reviews_distrubution.png
```

- udacity.ipynb ==> Notebook to investigate about point of interest.
- datos.csv  ==> Dataset with coordinates of point of interest.
- visualizations ==> Plots and graphs generated while analyzing data.

## Motivation
Working on these aspects related to business or real-world applications of how the data could be used:
- Prices Overview
- Listings count Overview
- Find busiest time of the year for this city
- Occupancy rate and Number of reviews over time
- Price Modelling

## Results
- The **busiest time** of the year is during `summer and winter(new year)`. 
- Most of the properties are booked and unvailable during this time, most of them are occupied and have **highest prices** in the year. 
- Property Price highly depends on the **neighbourhood**, the location where it is situated. `Downtown` in seattle has **highest rates**.
- The most **popular house size** in Seattle are houses for `2 or 4 persons`. 
- Tourist prefer to rent an entire house over a private room and a shared room. 
- `Number of bedrooms` is the **most influencing criteria** for *price prediction*.

## Creator

**Nilesh Sonawane**

- <https://github.com/s-nilesh>


## Thanks

<a href="https://airbnb.com">
  <img src="https://botw-pd.s3.amazonaws.com/styles/logo-thumbnail/s3/102014/airbnb.png?itok=d2X_Ds1a" alt="Airbnb Logo">
</a>

Thanks to [Airbnb](https://airbnb.com) for providing cool data!
