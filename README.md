# Graph_Project
Starting from a dataset of cities, the goal of this code is to create a graph where a city is connected to its three nearest cities. The user will need to input the IDs of two cities and/or the ISO2 code of a desired country. It will calculate and draw (in green) the shortest route (passing through the fewest number of nodes) between the two cities using an undirected graph. Using the directed graph, on the other hand, it will calculate, with good accuracy, one of the longest routes between two cities in the chosen country. In this case, the nodes will be colored blue. Finally, for both routes, the duration in hours will be calculated based on the following criteria: - 2 hours are required to reach the nearest city, 4 hours for the second, and 8 for the third; - 16 hours are required if traveling to a city that is not among the three nearest (only in the case of the undirected graph); - an additional 2 hours are required when crossing into another country and an additional 2 hours when traveling to a city with a population greater than 200,000 inhabitants.
