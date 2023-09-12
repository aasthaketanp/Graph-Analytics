# Graph-Analytics
A Comparative  Study On Network Analysis

# Graph-Analytics

A comprehensive study and analysis of various network properties and their applications across multiple categories of networks.

## Repository Contents
- [*Network Analysis Final Project.ipynb*](https://github.com/aasthaketanp/Graph-Analytics/blob/main/Network%20Analysis%20Final%20Project.ipynb) - Python code showcasing the detailed network analysis using NetworkX and Snap.py.
- [*A Comparative Study on Network Analysis.pdf*](https://github.com/aasthaketanp/Graph-Analytics/blob/main/A%20Comparative%20Study%20on%20Network%20Analysis.pdf) - The detailed report of the analysis and findings.

## Abstract

The project's main objective is to analyze network properties, including degree distribution, largest connected component size, clustering coefficient, and shortest path length. The study incorporates various networks like Human Social Network, Animal Network, Road Network, Authorship Network, and more. The networks were analyzed using NetworkX and Snap.py, and the results from both packages were compared.

## Key Findings
1. Both libraries (NetworkX and Snap.py) produce similar results for Degree Distribution, Clustering Coefficient, and Connected Components. However, a minor variation exists in the shortest path length distribution.
2. Snap.py consumes more memory for edge storage than NetworkX.
3. Snap.py is designed for distributed computing and would have potentially performed even better in terms of memory consumption and speed if used in a distributed environment.
4. Snap.py efficiently calculates all properties except for the Clustering Coefficient, which takes more time than NetworkX.
5. Network properties are not necessarily consistent across categories.
6. Snap.py excels in analyzing large graphs and computes properties faster for graphs containing thousands or millions of nodes and edges.

## Tools & Technologies
- *Python (3.8.10)*
- *NetworkX*
- *Snap.py*
- *Jupyter Notebook*

## Data Source
The data was sourced from [*KONECT Network Collection*](http://konect.cc/), with files in the `out.` format, which ranges from networks as small as 40 nodes to as extensive as 62,000 nodes.


## Future Work 
Considering Snap.py's design for distributed computing, there's potential for significant improvement when executed on a distributed system. Future studies might focus on how directed and undirected edges, as well as weighted and unweighted edges, play a role in analyzing network properties.


## *Contact*

To learn more about this project and others:

- [*Portfolio*](https://aasthakpatel.netlify.app/)
- [*LinkedIn*](https://www.linkedin.com/in/aasthaketanp/)
- [*GitHub*](https://github.com/aasthaketanp)
- [*My Resume*](https://aasthakpatel.netlify.app/images/AasthaPatelResume2024.pdf)

---

🌟 *Feel free to star the repository if you find it helpful!* 🌟
