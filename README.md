# Network_Security_Project
Visualize the internet architecture
We used Google Colab to create this project

## Configuration Instructions
Navigate to Google Colab, and signup to start working with Colab
Create new notebook and name it
Upload the dataset file into the environment from the below path
##### /content/routers_data_undirected

After all the configurations are set, we are ready to visualize the data

## Installation Instructions
We need to import all the below packages before visualizing the data
1. pandas
2. networkx
3. plotly.graph_objects
After installing the necessary packages, we do start coding
1. To create a graph object
2. We read the contents from the dataset file using pandas package
3. We use a function from_pandas_edgelist from netwrokx package to define source and target to plot a graph
4. We limited the nodes to 1200 in order to avoid complexity issues
5. We print dataframe just to confirm ![DataFrame](/DataFrame.jpeg)
6. We code 
6.1 The loop to find the degree of each node
6.2 The required properties like width of the connection, color, hover info, mode of the connected line
6.3 We implemented weighted edges between nodes
6.4 To show details like node_id, number of neighbouring nodes, number of node connections when we hover over each node
6.5 To plot the graph to visualize intensity



## Operating Instructions
We run all the code for output
1. To print dataframe
2. The loop that displays degree of a node with Visualization
3. To print the histogram

## Contributions
0 to 200             Lohith Bhargav Doppalapudi - R11786637
201 to 400           Deepika Duttaluru Muralidhar - R11798788
401 to 600           Bala Naga Sai Chandu Thutupalli - R11800450
601 to 800           Dharani Kumar Vemuri - R11804262
801 to 1000          Rajani Priya Danda - R11800015
1001 to 1200         Harshini Vemula - R11800661

## Contact for Authors
Lohith Bhargav Doppalapudi - R11786637
Deepika Duttaluru Muralidhar - R11798788
Bala Naga Sai Chandu Thutupalli - R11800450
Dharani Kumar Vemuri - R11804262
Rajani Priya Danda-R11800015
Harshini Vemula - R11800661
