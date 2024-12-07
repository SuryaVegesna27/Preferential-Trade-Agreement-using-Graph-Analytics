# Preferntial Trade Network Analysis with Community Detection
This project performs analysis and community detection on a global trade network using graph-tool and Louvain's method for detecting community structures, along with the Girvan-Newman algorithm for modularity. It provides visualizations and statistical analyses of trade relations, highlighting the identification of communities in the network and evaluating modularity.

# Prerequisites
Before running the project, ensure you have Python and the following libraries installed:
Required Libraries:
graph-tool: For advanced graph analysis and visualization.
pandas: For data handling.
numpy: For numerical operations.
matplotlib: For graph plotting.
networkx: For community detection with Louvain algorithm.
community: A package for applying the Louvain method.
python-igraph: For Girvan-Newman community detection.

# Project Structure
Graph Construction: The core of the analysis is based on a graph representing trade relations between countries. Each node represents a country, and each edge represents a trade agreement between countries. Various properties like trade depth and agreement types are associated with edges.

# Community Detection Algorithms: The project implements multiple community detection algorithms:

Graph-tool Blockmodel: Uses blockmodeling to find community structures.
Louvain Method: Applies modularity maximization to identify communities.
Girvan-Newman: A divisive hierarchical algorithm that detects communities based on edge betweenness.
Visualization: Graphs and communities are visualized using graph-tool's layout and drawing functions, with support for showing node attributes (e.g., country names).

# Steps to Run the Project
# 1. Prepare Graph Data
Before running the community detection algorithms, you must first build the trade graph (trade_graph) from your data. You should have a graph structure where nodes represent countries, and edges represent trade relationships.

# 2. Run Community Detection
Blockmodel Community Detection (Graph-tool)

# Louvain Method (NetworkX)
For community detection using Louvain's method, convert your graph-tool graph to a NetworkX graph and apply the Louvain algorithm

# Girvan-Newman Algorithm (igraph)
For Girvan-Newman community detection, use the igraph package to apply edge betweenness

# 3. Visualization
The code provides functionality to visualize the communities and the overall trade graph using graph-tool's graph_draw() function.

# 4. Run for Different Graph Subsets
Split the graph into different subsets based on conditions such as agreement years (e.g., before and after 2000).

# 5. Output
For each algorithm (blockmodel, Louvain, Girvan-Newman), the script will output:

Number of communities detected.
Modularity score (for Louvain and Girvan-Newman).
Visualization of the trade network with communities.
List of countries in each community.

# Visualization:
The script will generate images representing the trade network with communities visually distinguished.

# Conclusion
This project allows for the analysis and visualization of global trade networks using different community detection algorithms. By leveraging the power of graph-tool, networkx, and igraph, it enables the detection of meaningful groupings of countries based on trade agreements, providing insights into the global trade structure.
