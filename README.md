Path Finding Visualizer Project
====================
About the project
-----------------
In this project We challenged myself to learn and implement the most popular path-finding algorithms without looking at any online implementation,  
we have just looked at the theory of the path finding algorithms.

Requirements
------------
To run this code on your device is:
1. python
2. pygame library (for the graphics)

### Nodes  
The app contains 5 main node types to use:
* Normal node   (white)
* Start node    (blue)
* End node      (red)
* Obstacle node (black)
* Weight node   (Weight icon)

### Algorithms  
* Dijkstra
* A*
* Greedy

Controls
--------
### Drawing nodes  
First you need to choose the node type that you to draw by using the following controls:

|Node type|Keyboard key|
|---------|------------|
|  Start  |     S      |
|   End   |     E      |
|Obstacle |     O      |
| Weight  |     W      |



After choosing the a node type, hold the left mouse button and hover over the nodes you want to replace  
Use Right mouse button to remove Obstacle and Weight nodes

### Running the algorithm  
Choose the algorithm you want to use then press Enter

|Algorithm|Keyboard key|
|---------|------------|
|Dijkstra |     1      |
|   A*    |     2      |
| Greedy  |     3      |

### Other Controls
|   Function    |    Key     |
|---------------|------------|
|Reset          |     R      |
|Zoom in/out    |Mouse scroll|
|Increase delay |    Dot     |
|Dencrease delay|   Comma    |

Features
--------
1. The ability to Draw nodes
2. The ability to switch between three different algorithms
3. Obstacle and Weight nodes
4. Control the delay time/speed of the visualization
