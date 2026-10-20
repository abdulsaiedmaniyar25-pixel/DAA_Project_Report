# RouteWise – Smart Logistics Optimization

## Project Overview
RouteWise is a web-based logistics optimization application developed using Python, Flask, and NetworkX. It applies graph algorithms to optimize connections and routes between warehouse and delivery locations.

## Objectives
- Represent logistics locations as a weighted graph.
- Find the Minimum Spanning Tree to connect all locations efficiently.
- Calculate the shortest path between two locations.
- Evaluate delivery tours using the Travelling Salesman Problem (TSP).
- Demonstrate the practical application of Design and Analysis of Algorithms (DAA).

## Algorithms Used
- **Kruskal's Algorithm:** Finds the Minimum Spanning Tree (MST) with minimum total connection weight.
- **Dijkstra's Algorithm:** Finds the shortest path between two locations.
- **Travelling Salesman Problem (TSP):** Evaluates different visiting orders to find an efficient delivery tour.

## Technologies Used
- Python
- Flask
- NetworkX
- HTML
- CSS
- JavaScript

## Network Details
- **Locations:** 7
- **Road Connections:** 13
- **Total Original Edge Weight:** 44 units
- **MST Total Weight:** 14 units (6 edges)
- **Shortest Path:** Warehouse → City Center → East Hub → Airport Depot
- **Shortest Path Distance:** 7 units
- **TSP:** Evaluates 720 possible visit orders with a fixed starting location.

## Project Purpose
RouteWise demonstrates how graph theory and algorithmic techniques can support logistics route planning and optimization using sample network data.
