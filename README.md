# Node-level Associations Between Cell Types And Connectivity


The goal of this research project is to explore the internal relationships of __brain cell types__ and __connectivity__. We aim at two things in major: 

1. Finding a robust way to predict structural connectivity using cell type densities in mouse brain

2. Transferring the findings to human brain.

## Overview: 

We consider this as a graph problem: Among the brain, there are many different Region of Interests (ROIs). In the mouse brain research, we split the brain into 424 ROIs following the mouse Common Coordinate Framework (CCF). Then we obtain regional densities that could be used as input features in our machine learning approach. In this way, the brain connectivity network is translated into a graph with 424 nodes connected by many edges. For each node, there are 25 node features representing the density of each cell type.




## Recommended steps of working on this project: 


1. Read the paper preprint pdf provided in this repo. You don't have to understand every bit of it. However, it's crucial to have a general understanding of the problem as well as the metadata. The original paper addressed that the existence of connectivity between nodes (namely the connection of ROIs) rely on the densities of cell types in those ROIs. We will explore further on this basis.

2. Download this GitHub repo -- this provides you the datasets as well as some skelenton notebooks. A thorough guide of using GitHub can be found here[https://phoenixnap.com/kb/how-to-use-git]. 

 - To simplify the collaboration process, please create a branch of your name once you have started coding. Update your progress every time by doing `git commit -m "explanation of this update"` and `git push `. 
 - Daren will go through the codes and merge the branches into main branch every Friday.

3. Run the Begginer's Guide Jupyter Notebook. Make sure that you have installed the necessary libraries. Use `pip install XYZ` if missing any dependency.

4. Understand the dataset. Play with it a bit. Learn the definition of graph attributes and run some customized analysis.  


## Required Techniques: 
- Git & GitHub
- Jupyter Notebook
- Numpy, Pandas
- Scikit-Learn or other Machine Learning packages



## Weekly Meeting: 
10: 00 PST (12:00 CT) every Wednesday.
