# Social Media Analytics — Lab 1

## Social Network Main Parameters: Calculation and Visualization

This repository contains the implementation and analysis for Lab 1 of the
Social Media Analytics course.

The objective of this laboratory work is to construct and analyze a social
network using graph-based methods and calculate the main node and network
parameters.

## Dataset

The analysis uses the `GOT-book1.csv` dataset, which represents relationships
between characters from the first book of the *A Song of Ice and Fire* series.

The dataset contains:

- **187 nodes (characters)**
- **684 edges (relationships)**
- Undirected relationships
- Relationship weights

The network was represented using an adjacency matrix and visualized as a
graph.

## Parameters Calculated

### Node Parameters

The following node-level parameters were calculated:

- Degree
- Distance
- Closeness
- Betweenness centrality
- Clustering coefficient

### Network Parameters

The following network-level parameters were calculated:

- Diameter
- Degree centralization
- Maximal cliques
- Network clustering coefficient
- Modularity
- Community structure

## Main Results

| Parameter | Result |
|---|---:|
| Nodes | 187 |
| Edges | 684 |
| Connected components | 1 |
| Diameter | 7 |
| Degree centralization | 0.3189 |
| Maximal cliques | 245 |
| Largest clique | 10 |
| Network clustering coefficient | 0.5121 |
| Communities | 7 |
| Modularity | 0.4352 |

### Most Connected Characters

According to degree centrality:

1. Eddard-Stark — 66
2. Robert-Baratheon — 50
3. Tyrion-Lannister — 46
4. Catelyn-Stark — 43
5. Jon-Snow — 37

## Technologies

- Python
- Google Colab
- pandas
- NetworkX
- Matplotlib

## Project Files

- `Social_Media_Analytics_Lab1.ipynb` — complete analysis and visualization
- `GOT-book1.csv` — dataset used for the analysis
- `requirements.txt` — Python dependencies

## Running the Project

The notebook can be opened directly in Google Colab.

Alternatively, install the required Python packages:

```bash
pip install -r requirements.txt
