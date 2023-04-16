# Manifold Learning and Diffusion Maps

------------------------------------------------------------------------------------------------------------------------------------------------

![alt text](https://d3i71xaburhd42.cloudfront.net/100dcf6aa83ac559c83518c8a41676b1a3a55fc0/3-Figure1-1.png)


## Anshika Agrawal, Bryan Munoz, Nubaira Milki, Krutal Patel 


In manifold learning one assumes that data given in high-dimensional spaces in fact is on (or concentrated around) a lowdimensional regular set, namely a manifold. 

### Techniques Explored
1. T-distributed Stochastic Neighbor Embedding
2. Isometric Mapping
3. Laplacian Eigenmaps
4. Diffusion Maps


Diffusion Maps has been applied in a very large variety of settings beyond manifold learning, since it can be adapted to dynamical systems (from molecular dynamics (e.g. Determination of reaction coordinates via locally scaled diffusion map, to single cell trajectories and to signal processing on graphs (e.g. The Emerging Field of Signal Processing on Graphs).

### Algorithm
1. Deployed several toolboxes for each algorithm on real world datasets including Vehicle Loan Default, Credit Card Dataset, Single Cell Trajectories, 
2. Discussion on the computational complexity of the different algorithm

### Data Exploration
Various Datasets were chosen and analyzed from a variety of different industries including biology, finance, and English Literature. Each of these datasets had to be preprocessed before the algorithm was deployed.

Preprocessing
1. Data Imputation: useing column mean for NaN; regression accross the attributes
2. Data Standardization / Regularization 
3. Random Sampling to extract training and testing sets

Connections with the course. Multi-Dimensional Scaling; random projections; graphs and networks; Markov chains;
spectral clustering. 
