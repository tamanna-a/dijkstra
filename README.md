
<div><h1>Dijkstra's Algorithm</h1>

<p>In this project, we implement Dijkstra's algorithm to find shortest paths between pairs of cities on a map. It includes a GUI that lets you visualize the map and the path your algorithm finds between two cities.</p>

<p>The directory includes: </p>
- <code>cityxy.txt</code> - a list of cities and their (X,Y) coordinates on the map. These are the vertices in the graph. 
- <code>citypairs.txt</code> lists direct, connections between pairs of cities. These links are bidirectional, if you can go from NewYork to Boston, you can go from Boston to NewYork. These are the edges of the graph.</p>

- <code>Vertex.java</code> and <code>Edge.java</code>, which represent the vertices and edges of a graph. </p>

- <code>Dijkstra.java</code>, which represents a graph and contains implementation of Dijkstra's algorithm. 

<p>Compile all Java sources and run the program <code>Display</code>. At this point, click on the &ldquo;Box URL&rdquo; button along the Codio tool bar at the top of your screen. This should bring up a view of the computer's actual desktop screen. Inside, a window will have appeared with your running program that displays the map. 