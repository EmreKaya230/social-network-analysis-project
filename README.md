# Project Overview

Analysis of a large-scale Facebook social network (50,515 nodes, 819,306 edges) to identify influential users using graph-based metrics.

# Network Summary

Nodes: 50,515 users
Edges: 819,306 connections
Connected: Yes (single component)

# Key Findings

Top influencer (PageRank): Node 48099 with score 0.000840 — highest centrality in the entire network
Top bridge node (Betweenness): Node 2568 with score 0.0301 — most critical connector between communities
Top eigenvector node: Node 17590 with score 0.289 — most connected to other important nodes
Node 26836 appeared in both Betweenness and Eigenvector top 10 — consistently influential across metrics

# Methods

PageRank — identifies globally influential nodes
Betweenness Centrality — detects bridge nodes between communities
Eigenvector Centrality — finds nodes connected to other important nodes
Degree Distribution — visualizes connectivity patterns

# Tech Stack
Python, NetworkX, Pandas, Matplotlib

# Dataset Source

https://snap.stanford.edu/data/gemsec-Facebook.html
