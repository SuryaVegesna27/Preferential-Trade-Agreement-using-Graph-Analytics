# Preferential Trade Network Analysis with Community Detection
Explore the dynamics of global trade through network analysis and community detection. This project leverages advanced graph analysis techniques to identify and visualize community structures within international trade networks, providing insights into trade relations and their evolution.

# 🔍 Project Overview
This analysis employs various graph-based community detection algorithms, including Louvain's Method, Girvan-Newman Algorithm, and Graph-tool Blockmodeling, to uncover meaningful groupings of countries based on trade agreements. 

# Key outcomes include:

Community Identification: Detect distinct trade communities and evaluate modularity.

Visualizations: Generate compelling graphical representations of trade relations and detected communities.

Statistical Analysis: Measure network properties and modularity scores for deeper insights.

# 📦 Prerequisites
Ensure you have Python installed along with the following libraries:

graph-tool: For advanced graph analysis and visualization.
pandas: For data handling and manipulation.
numpy: For numerical computations.
matplotlib: For creating plots and visualizations.
networkx: For implementing the Louvain algorithm.
community: For applying Louvain's method to detect communities.
python-igraph: For Girvan-Newman community detection.

# 📂 Project Structure
1. Graph Construction
Build a graph where nodes represent countries and edges represent trade agreements.
Annotate edges with properties such as trade depth and agreement types.

2. Community Detection Algorithms
Graph-tool Blockmodel: Leverages blockmodeling to identify community structures.
Louvain Method: Utilizes modularity maximization for community detection.
Girvan-Newman Algorithm: Applies a hierarchical approach using edge betweenness.

3. Visualization
Use graph-tool for graph layout and drawing.
Highlight nodes (countries) and edges (agreements) with community-specific colors.

# 🚀 Steps to Run the Project
1. Prepare Graph Data
Construct a graph (trade_graph) where:
Nodes = Countries.
Edges = Trade agreements.
Ensure edge properties like trade depth and agreement types are included.

2. Run Community Detection
Blockmodel (Graph-tool): Apply blockmodeling for structural analysis.
Louvain Method (NetworkX): Convert the graph to a NetworkX format and apply the Louvain algorithm.
Girvan-Newman (igraph): Use igraph for hierarchical community detection.
3. Visualization
Generate visual representations using graph-tool’s graph_draw() function.
Highlight communities with distinct colors and annotate nodes with country names.
4. Analyze Subsets
Split the graph into subsets (e.g., agreements before/after 2000) for comparative analysis.
5. Output
Number of Communities: Detected by each algorithm.
Modularity Scores: For Louvain and Girvan-Newman.
Community Visualizations: Images of the trade network with communities distinguished.
Community Lists: Countries grouped into communities.

# 🖼️ Visualization
The project produces intuitive visualizations, such as:

Trade networks with communities differentiated by color.
Subset-specific visualizations for comparative analysis.

# 📊 Key Features
Comprehensive trade network analysis using multiple community detection algorithms.
Intuitive visualizations of global trade dynamics.
Modularity scoring to assess community cohesiveness.
Insights into the evolution of trade relations over time.

# 🤝 Conclusion
This project provides a robust framework for analyzing and visualizing global trade networks. By combining the power of graph-tool, NetworkX, and igraph, it delivers meaningful insights into international trade structures and the evolving patterns of preferential trade agreements.

