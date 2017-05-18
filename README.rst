Social Network Analysis with Python and NetworkX
================================================

Materials for the PyData Barcelona 2017 workshop on Network Analysis with Python and NetworkX.

Abstract
--------

Social Network Analysis (SNA) has a wide applicability in many scientific fields and industries. This workshop is a gentle introduction to SNA using Python and NetworkX, a powerful and mature python library for the study of the structure, dynamics, and functions of complex networks. Participants in this workshop should have a basic understanding of Python, no previous knowledge of SNA is assumed.

For this workshop attendees will need to install NetworkX (>=1.11), Matplotlib (>=1.5), numpy (>=1.10) and have a working Jupyter Notebook environment. Some examples will also use Pandas (>=0.17) and Seaborn (>=0.7), but these packages are not essential. Only basic Python knowledge is assumed.

Outline of the workshop
-----------------------

1. Brief Introduction to Graph Theory
    * Mathematical foundation of Social Network Analysis.
    * Why graphical representations usually doesn't help much.    
2. Creating and Manipulating Graphs
    * Data Structures: Graphs, DiGraphs, MultiGraphs and MultiDiGraphs.
    * Adding nodes and edges.
    * Adding and updating node and edge attributes.
    * Graph generators.
    * Visualizing graphs using Matplotlib.
    * Common formats for reading and writing Graphs. 
3. Network Analysis
    * Basic concepts: Degree.
    * Distance measures: paths, simple paths, and shortest paths.
    * Node centrality analysis: measures and their relation.
    * Analyzing groups and subgroups: Cliques, k-cores, components, and k-components.
4. Bipartite Graphs
    * Definition of bipartite networks and their use in modeling group affiliations.
    * Working with bipartite networks with NetworkX.
