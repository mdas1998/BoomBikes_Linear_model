# Bike Sharing Assignment
> A multi linear regression model has been built as part of this assignment which will help us to identify the demand for shared bikes.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The assignment will use multi linear regression model to identify the demand for shared bikes. 
- We have a dataset called day.csv which contains historical data of previously booked rental shared bikes and various factors involved which could effect the demand like temperature, weather situation, holiday etc. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
The following are the factors which has drastic effects on the target variable cnt:
- Season (season4) - A coefficient value of 0.1033 indicated that a unit increase in season4 variable increases the bike hire numbers by 0.1033 units.
Temperature (temp) - A coefficient value of 0.5843 indicated that a unit increase in temp variable increases the bike hire numbers by 0.5843 units.
- A coefficient value of -0.2578 indicated that, w.r.t Weather3, a unit increase in Weather3 variable decreases the bike hire numbers by -0.2578 units.
- Year (yr) - A coefficient value of 0.2334 indicated that a unit increase in yr variable increases the bike hire numbers by 0.2334 units.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - 3.9.12
- Pandas - 1.4.2
- Numpy - 1.21.5
- Matplotlib - 3.5.1
- Seaborn - 0.11.2
- Sklearn - 1.2.2
- statsmodels - 0.14.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@mdas1998] - feel free to contact me!

