# Shortest-Path-Problem-Artificial-Intelligence-

# OUTPUT:
# _______
![image](https://user-images.githubusercontent.com/92660593/220958114-2dc6e780-bcc0-4eed-b5d9-03a41cc11d9f.png)

# Explanation of the code:
# ________________________
•	This code implements two search algorithms, namely Depth First Search (DFS) and Breadth First Search (BFS), to find the shortest path between two cities in Romania.
•	The graph_mentioned_in_question is a dictionary that represents the graph, where the keys are the names of the cities and the values are lists of tuples containing the neighboring city and the cost to travel to that city.
•	The depth_first_search function implements the DFS algorithm to traverse the graph. It takes the graph_mentioned_in_question, start and end nodes as input parameters. The algorithm uses a stack to keep track of the visited nodes. It starts at the start node and explores all its neighbors, adding them to the stack. It then pops a node from the stack and explores its neighbors until it reaches the end node or there are no more unvisited nodes left. The algorithm keeps track of the path taken and the cost of the path.
•	The breadth_first_search function implements the BFS algorithm to traverse the graph. It takes the graph_mentioned_in_question, start and end nodes as input parameters. The algorithm uses a queue to keep track of the visited nodes. It starts at the start node and explores all its neighbors, adding them to the queue. It then dequeues a node from the queue and explores its neighbors until it reaches the end node or there are no more unvisited nodes left. The algorithm keeps track of the path taken and the cost of the path.
•	The source and destination variables represent the starting and ending cities.
•	Then we used BFS algorithm to find the shortest path and its cost between the source and destination nodes. The BFS algorithm traverses the graph in a breadth-first manner it explores all the nodes at the current level before moving to the next level. The breadth_first_search function takes the graph, source node, and destination node as input and returns the shortest path and its cost.
•	Then we used DFS algorithm to find the shortest path and its cost between the source and destination nodes. The DFS algorithm traverses the graph in a depth-first manner it explores the deepest node first before backtracking to explore the other nodes. The depth_first_search function takes the graph, source node, and destination node as input and returns the shortest path and its cost.
•	Finally, the code computes the shortest path and its cost using both DFS and BFS algorithms and prints them to the console.
