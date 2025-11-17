# DataScienceAssignment
Repository Containing Files for Shubham Sharma's Data science assignment tackling the Karate Club community problem

## Course Information
**Course:** DSC212: Graph Theory  
**Topic:** Spectral Modularity Analysis on Zachary's Karate Club Network

## Project Description
This project implements spectral modularity partitioning to analyze community structure in Zachary's famous Karate Club social network. The analysis uses recursive eigenvalue-based splitting to identify natural divisions in the network, mirroring the real-world split that occurred in the club.

## Repository Contents
- `karate_club_modularity.ipynb` - Main Jupyter Notebook containing all analysis
- `README.md` - This file
- `.gitignore` - Git ignore configuration

## Notebook Contents
The Jupyter Notebook includes:

1. **Algorithm Implementation** - Recursive spectral modularity partitioning using the modularity matrix
2. **Visualization** - Graph visualizations at each split showing community evolution
3. **Metric Analysis** - Tracking of centrality measures (degree, betweenness, closeness) and clustering coefficients
4. **Metric Evolution Plots** - Line plots showing how node metrics change across iterations
5. **Discussion** - Analysis of results, focusing on key nodes and metric changes during community splits

## Requirements
- Python 3.x
- networkx
- numpy
- matplotlib
- pandas


## Reference
Newman, M. E. J. (2006). "Modularity and community structure in networks." *Proceedings of the National Academy of Sciences*, 103(23), 8577-8582.
