
# Flight Price Prediction

Ansh Bangia 101803628

Enter details of your flight like source and destination, departure and arrival dates, airline, etc. to find out an appropriate price for your flight.

This will be a regression problem since the target or dependent variable is the price (continuous numeric value). ‘Price‘ will be our dependent variable and all remaining variables can be used as independent variables. ‘Total_Stops‘ can be used to determine if the flight was direct or connecting.




## Live Link

https://flight-cost-pricing.herokuapp.com/

  
## Methodology Flowchart

![FLOW CHART](images/flowchart.png)
  
## Optimizations

* Modifying the dataset to better use the provided data about date of flight.
* Tuning of hyper parameters (n_estimators, max_features, max_depth, min_samples_split, min_samples_leaf) of Random Forest Regressor using RandomizedSearchCV.

  
## Screenshots

![image](https://user-images.githubusercontent.com/68856038/137435406-ea962c4f-4f18-4738-ad32-249a2b767361.png)

  
