# Flight Delays and Cancellations Analysis



## Problem Statement
The project aims to analyse the 2015 Flight Delays and Cancellations dataset provided by the Department of Transport. The dataset contains information about flight details such as flight code, departure and arrival times, delay, distance between the source and destination airports, airtime, airlines' data, and airport’s data. 

We need to clean the data and find insights like ranking airlines based on their punctuality, finding the optimized route between two airports using airtime, and predicting flight delays using machine learning models.

## Proposed Approach
- Task 1 - To predict the delay of the flight we have used machine learning algorithm. We used decision tree classifier for this.

- Task 2 - To rank airlines based on punctuality of the flights, we have calculated the average delay of each airline and used it as one of the parameters in ranking.

- Task 3 - To find the optimized route between two airports, we used algorithm Dijkstra's algorithm to find the shortest path between two airports. We have built a graph for Dijkstra algorithm in which each node represents the airport and the edge between them is route which has airtime as a weight. To predict flight delays, we have trained a machine learning model on the given data to predict the delay of flights.



## Project structure


- Code files are inside code folder

- CSV, are inside flight_data folder


## how to run

- install pyspark and jyupter notebook
- open the data cleaning ipynb and run it 
- now run the ranking ipynb file for task1
- run path finding finding ipynb for task2
- run the machine learnin ipynb file for task 3
