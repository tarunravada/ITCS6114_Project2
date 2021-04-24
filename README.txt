Files
------------------------
RunMST.ipynb
MST_utils.py
RunShortestPath.ipynb
ShortestPath_utils.py

Data
------------------------
MST1, MST2, MST3, MST4 - Test files for MST
SP1, SP2, SP3, SP4 - Test files for Shortest Path

To test Shortest path
---------------------------------------------------------------
Run the RunShortestPath.ipynb notebook.
Details to use different input files are included in the notebook.
	The variable path is set to ‘data/’. If input files are placed elsewhere, change this variable to point to the relative path.
	Choose among input1, input2, input3, input4 to run the program for various inputs and pass it to runShortestPath() function.
ShortestPath_utils.py contains the implementation of Dijkstra’s algorithm and the Graph data structure. 

Note: The algorithm requires a specific input format. Input vertices must be numbers only. Please refer to the provided input files for example.

Sample input format:
9  21  D
1  2  8
1  6  13
	
To test Minimum Spanning Tree
---------------------------------------------------------------
Run the RunMST.ipynb notebook.
Details to use different input files are included in the notebook.
	The variable path is set to ‘data/’. If input files are placed elsewhere, change this variable to point to the relative path.
	Choose among input1, input2, input3, input4 to run the program for various inputs and pass it to runMST() function.
MST_utils.py contains the implementation of Kruskal’s algorithm and the Undirected graph data structure. 

Test of different Input Files
---------------------------------------------------------------
Tests on four different graphs for both algorithms can be seen in RunMST.ipynb and RunShortestPath.ipynb files.
