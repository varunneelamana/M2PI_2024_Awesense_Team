# M2PI_2024_Awesense_Team

time_series_split_branches.ipynb:

This file includes several scripts - 
1. Finding the first split after the root (grid_element_id)
2. Finding all places after the root where phase changes from ABC to non-ABC
3. Finding all places after the root where phase changes from ABC to non-ABC, with number of meters in each cluster and their total consumption
4. Finding all places after the root where phase changes from ABC to non-ABC, with consumption per cluster per timestamp

time_series_split_branches_Laminar.ipynb:

This file gives a laminar set of clusters in the following way:
Level 0 - all the clusters under the root.
Levels 00, 01 - all the clusters in each branch after the first bifurcation.
Levels 000, 001 and 010, 011 - all the clusters in each branch after the second bifurcation (or after the first bifurcation in each branch).
And so on.
So levels 00 and 01 are a subset of level 0, but level 0 might have some more clusters if they appear before the bifurcation.
