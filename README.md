# Energy-output-prediction

About Data

The data is downloeded from UCI Machine Learning Repository, it contains 9568 data points collected from a Combined Cycle Power Plant over 6 years (2006-2011),
when the power plant was set to work with full load. Features consist of hourly average ambient variables Temperature (T),
Ambient Pressure (AP), Relative Humidity (RH) and Exhaust Vacuum (V) to predict the net hourly electrical energy output (EP) of the plant.

Attribute Information

Features consist of hourly average ambient variables 
- Temperature (T) in the range 1.81°C and 37.11°C,
- Ambient Pressure (AP) in the range 992.89-1033.30 milibar,
- Relative Humidity (RH) in the range 25.56% to 100.16%
- Exhaust Vacuum (V) in teh range 25.36-81.56 cm Hg
- Net hourly electrical energy output (EP) 420.26-495.76 MW

Goal

My goal for this project is to apply different Machine Learning Regression Algorithms to see which algorithm perform better
in predicting the electrical energy output value(EP). 

Algorithms to try:

- Multiple linear Regression 
- Random Forest Regression
- Support vector regression
- Polynomial Regression
- Decision Tree Regression

