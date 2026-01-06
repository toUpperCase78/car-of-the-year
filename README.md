# Car of the Year

**Datasets &amp; Analyses of Car of the Year Awards**

![Car of the Year 2025](CarOfTheYear_2025_logo.png)

## About

The **Car of the Year** is internationally recognized organization that annually awards the prestigious trophy for the car manufacturers that produced the most exceptional new car released in the European market.

In the last decade, every year about 30 candidates are determined in provisional evaluation. Later, several of them are selected to be nominees (up to 7 cars), and points are given to each one by over 50 juries from many different European countries, with regards to engine, performance, handling, comfort, exterior-interior design, easiness and innovative technologies. Finally, in a well-known car exhibition that is organized within the same year, the winner is announced to claim the Car of the Year title.

_This repository is the **remake version** of my previous implementation that was uploaded more than 5 years ago; now with up-to-date information, all voting grids for all nominated cars between 1995 and 2025, as well as the images of all winner cars spanned from the first organized year to the latest one._

The datasets and the data inside were all collected from the Official Car of the Year [Website](https://www.caroftheyear.org).

## Datasets

Here, two different types of datasets can be found:

* **The first type** (`CarOfTheYear_Winners_Nominees.csv`) encompasses all winners and nominees with their total points, starting from 1964, up to the present. Inside, the order of the columns first show the year individually, then the winner car with its accumulated point (separated into two distinct columns), then the second-placed one with its total point, and so on.
* **The second type** (`CarOfTheYearXXXX_VotingGrid.csv`) contains voting grids for all nominated cars, between 1995 and 2025 (total of 31 datasets are available). In these datasets, each row begins with the country and name of the jury, then his/her point distribution to all nominated cars. It can be recognized accordingly that the leftmost column represents the points given by each participated jury to the award-winning car, then the points to the second-placed car, up until the points distributed for the last-placed one. Thus, the columns of all nominated cars have been set to reflect this ranking order.

## Analyses

There is only one data analysis I had carried out in 2020, evaluated between the years 2010 and 2020: `CarOfTheYear_Winners_Nominees_2020.ipynb`

Once the 2026 winner has been announced, there will be another analysis in much broader area to inspect everything between 1995 and 2026. Stay tuned!
