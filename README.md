# Random Maze Solver in Java
</br>
-----------------------------------------------------------------------
Compile and Run
-----------------------------------------------------------------------
1) Open a command prompt.</br>
2) Clone this repo.</br>
3) Compile using java.</br>
% javac MazeSolver.java.</br>
4) Run program.</br>
% java MazeSolver.</br>
</br>
-----------------------------------------------------------------------
How to use
-----------------------------------------------------------------------
1) Reset will reset the board to a blank board.</br>
2) Mark slowly will mark the paths that are going into the queue.</br>
3) Mark will immediately mark all paths even if mark slowly is running.</br>
4) Stop will halt the program and cause it to need to be reset.</br>
5) Show Shortest Path after marking the positions will show the shortest path.<br>

-----------------------------------------------------------------------
Summary
-----------------------------------------------------------------------
This is a program that will generate random mazes to be solved. The program uses a queue data structure to solve and will add surrounding possible locations. Then, dequeue and do the same for the dequeued block, reapeat until queue is empty. Once the queue is empty the program finds the largerst position and trasverses backwards.
