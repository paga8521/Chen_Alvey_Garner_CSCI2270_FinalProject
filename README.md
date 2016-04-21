# Chen_Alvey_Garner_CSCI2270_FinalProject
final project
team members: Jinhong Chen, Justin Eric Alvey , Patrick Micheal Garner
in our project, we have different ideas, thus, we are going to write our own 
code and then combine our ideas by using different txt files to run different programs.
 First, for me , Jinhong, i'm going to write a c++ programming which can store 
data into graph structure, so , i will also create a cites graph and label the 
distance between them, then, you can select the starting place and the destination
, by using the cities graph, it can assign districts for the connected cities, 
select the distance bewteen two cites, display the paths, add the vertex.edg, find 
the shortest distance,the most intereting part is the signal part, i will assgin 
someone has a mobile or some other devices with the signls, these signls's range can 
be selected, and then, from the starting place, i will draw a circle to list the 
cities in that range, from these cities, they will be regarded as starting place 
for next step, thus, in order to reach the destination, it will select the lanes 
for that guy who has that signals ,(these signals cannot reach the signl outside that 
range circle, so only the cities in that circles can be listed) and list all of these 
paths. 

Justin: When I thought of this project, I wanted to develop some sort of game for others to play.
My idea is a mix of several ideas: to create a game that asks users survey/trivcia questions about
popular movies. The user can choose to dine or go to different theaters in an area, and the different 
regions will each have different movies to see. Different regions will have different movies, and 
thus harder questions. The idea combines the idea of a graph (map of several cities, a class), a class
of the movie inventory, a struct for each movie data structure, and public methods to add movies, 
change regions, and others. They could be songs - like guess the lyrics, or stories where you answer
trivia questoins about the story.  

Patrick: My idea was to build off of one of the past assignments, specifically the binary tree movie project.  My idea was to create a library of songs or movies, and to have separate functions that would build the binary tree in different fashions, changing the way in which the movies or songs were organized.  For example, they could be organized by genre and then alphabetically within each genre.  Each movie node would also include a "display similar movies" which would randomly select 5 movies with the same genre and list them as suggestions. 

Final decision:

We decided to build on Jinhong's idea of implementing a graph with extra functions.  We have also added the option to add in services in each city.  These services list a name and a cost, such as 'gas' for $'20'. This helps the user "plan a road trip" based on which services are in which city.
