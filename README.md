### A* Search Algorithm – Delivery Route Optimization

## Project Overview
This project implements the A* (A-star) search algorithm in Python to determine the optimal delivery route between locations in a weighted graph 
representing a delivery network. The system uses heuristics and path cost calculations to efficiently find the shortest path from a starting point to a destination.

## Problem Context
A delivery truck must travel between towns in the Mahikeng local municipality. Each location is represented as a node in a graph, and roads between
locations are weighted based on distance (cost).

The goal is to compute the least-cost path from a start node (Disaneng) to a destination node (Coligny).

## Algorithm Used

A* Search Algorithm
A* uses the evaluation function:
f(n)=g(n)+h(n)
Where:
g(n) = cost from start node to current node
h(n) = heuristic estimate from current node to goal
f(n) = estimated total cost of path through node

## Features
- Weighted undirected graph representation of locations
- Custom heuristic values for each node
- A* pathfinding implementation
- Tracking of visited nodes (exploration order)
- Reconstruction of optimal path
- Simulation of truck movement step-by-step
- Total cost calculation of optimal route

## Key Concepts Demonstrated
- Graph theory (nodes and weighted edges)
- Heuristic search strategies
- Priority queue implementation (heapq)
- Pathfinding algorithms (A*)
- Algorithm optimization techniques
