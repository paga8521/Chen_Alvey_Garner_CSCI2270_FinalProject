# Chen_Alvey_Garner_CSCI2270_FinalProject
CSCI 2270 Final Project

Members:

 Jinhong Chen
 Justin Alvey
 Patrick Garner
 
Summary:
 
 This program is an extension of assigment 10.  The program will read in a graph from a .txt file(data2.txt) which is
 provided in the project folder.  From here, the program includes functionality where the user can determine the shortest
 distance between 2 designated cities, add cities and edges, as well as display all information as a whole or for each
 vertex(city).  The program also has the ability to split up the cities into districts, if the user adds in cities that do
 not connect to the cities provided in the text file.  One unique function included in this program is the ability to set a
 distance limit.  The user gets to submit a starting city, a target city, and a distance limit, and the program will
 determine whether or not there is a path that exists and does not exceed the given distance limit.  If there is a path
 that doesn't exceed the limit path, then the program will provide the user with the distance of the path between the two
 chosen cities.  Another set of unique functions provided in this program are the implementation of services.  Services are
 things such as gas, movies, national parks, lodging, etc., that are provided at a city(vertex).  These services can be 
 added only by the user through the 'Plan a trip' option in the main menu.  It will then pull up a new menu for service 
 functionality.  From here the user can define services to help them plan a road trip.  This is useful as a tool to help the user organize their ideas as they do external research on each city.  
 
Further Instruction:
 
 The arguments for the program are as follows:
 
  data2.txt
  
 This is needed to run the program properly, as this initiates the graph.  The main menu contains all options to add and determine information of vertices as a whole.  To take advantage of the services functionality, the user must activate the second menu by choosing option 10, titled 'Plan a trip'.
