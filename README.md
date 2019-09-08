
## Predictive Maintenance
With increased number of flights, it is very essential that the engines are monitored regularly. 
The engine should not break down before scheduled maintenance. Breakdown can cause serious issues during a flight. 
The maintenance cost will increase too. Manual predictive maintenance is very costly. 
It requires labor and is not effective at finding the issues. 
We need condition based maintenance instead of time based maintenance. 
Prognostic analysis of various parameters of the engine can help us to improve the availability of the engine 
and reduce maintenance costs.

Engines have a progressive degrading pattern. These patterns can be easily found from the sensor measurements. 
Machine learning can use the historical data to compare sensor readings and failure events. 
Using this data, machine learning can predict when the engine will fail based on the live sensor readings. 
In this project, I worked on various predictive maintenance solutions. The predictive maintenance solutions are as follows:-

1) Predict remaining useful life of an engine (Regression)
2) Predict if an engine will fail within a particular time period e.g. 30 days (Binary Classification)
3) Predict if an engine will fail in different time periods e.g. fails in time period 0 to 15 days or 15
to 30 days or greater than 30 days (Multi class Classification)

The goal is to experiment with different ways of assigning the label, to see what gives the best accuracy. 

Tasks involved for the above 3 predictive maintenance solutions are as follows:-

* Download and preprocess Turbofan engine C-MAPSS data set 
* Visualize the data
* Identify benchmarks
* Feature Transformation
* Model Selection
* Train and evaluate the model


### Getting Started
Upload CMAPSSData folder and predict.ipynb to jupyter notebook server (both should be in the same directory). 
Then open predict.ipynb and execute each statement in the notebook.