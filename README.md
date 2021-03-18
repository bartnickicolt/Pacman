# Pacman
A pacman game developed in my Artificial Intelligence class spring semester 2021

Feb 11, 2021
This is the end of the third session on working on this project to include searching for the corners of the maps, traversing to each of the corners, and eating the dots that are placed on the maps by the given code.  The first problem on this portion of the homework was to find all the corners of the map that was given.  How I went about solving this was to establish where the start state was and what the goal state was and once we know that we essentially just keep moving until we have visited all the corners and we can find the goal state in our visited states list.
The second problem was to create a heuristic for the program to find the corners in the most efficient way possible.  I essentially did the same thing as just finding the corners but when we start we first find which corner is closest to the starting point and traverse to that corner first.  Once we have visited that corner we remove it from the un-visited corner list I had created and then found which corner was closest to our current position to traverse to next.  We repeat this until we finally remove all corners from the un-visited list and we have our end goal.
The third problem was to find and eat the dots.  How I ended up creating the heuristic for this one was to do essentially the same thing for the corner heuristic.  Once we know the starting point we go to the dot that is the closest distance and go that direction.  For some reason it does leave a few dots on the other side of the map to pursue others but it is more efficient than I had originally thought it would be.
March 18, 2021
This adds in two files to include value iterating agents and an analysis of bridge crossing.
