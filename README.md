# 20155087_Saumya_Zorang_Assignment-

CASE-I : When input is provided 

EXPLANATION :
•	First we need to create a structure that has the coordinates 
•	After this we will create a function to calculate the distance between the two points
•	Then we will create the Nearest Neighbor Function which implements the nearest neighbor algorithm to find a route starting from the given index (start) that visits all points and returns to the starting point.
•	The function uses a greedy approach to iteratively select the nearest unvisited point from the current point until all points are visited. The result is a vector representing the order of points to visit.
•	In the main function we need to put the coordinates of the places where the packages need to be delivered and add the store location at the end.
•	After that, we need to set up some basic information like the number of delivery agents and the total number of orders.
•	Using the "nearest neighbor," approach we can figure out the best routes for each delivery person to take.
•	These routes start and end at the store.


CASE – II : When input is included via an external file 

Explanation :
•	First we will include the external file “addresses.txt”
•	Then we will create a structure that has the coordinates 
•	After this we will create a function to calculate the distance between the two points
•	Then we will create the Nearest Neighbor Function which implements the nearest neighbor algorithm to find a route starting from the given index (start) that visits all points and returns to the starting point.
•	The function uses a greedy approach to iteratively select the nearest unvisited point from the current point until all points are visited. The result is a vector representing the order of points to visit.
•	In the main function, we will open the file "addresses.json" to get the locations where packages need to be delivered and if the file could not be opened then error message will be generated. 
•	Next, we will read the latitude and longitude coordinates from the file and save them in a list and add the store location. 
•	Then, we will create variables for number of delivery agents and the total number of orders.
•	Using the "nearest neighbor," algorithm we will figure out the best routes for each delivery person to take and these routes start and end at the store.


