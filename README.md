# Manifold Learning and Diffusion Maps

------------------------------------------------------------------------------------------------------------------------------------------------
## Repo Instructions
Since 4 people will be adding code to the same files using the same datasets, follow these steps:
1. Clone the repo (it will default to the main branch)
```
git clone https://github.com/krutalp/MCFDS-Manifold-Learning.git
```

2. Locally: create a new branch with the title of the issue (see issues tab)
```
git checkout -b issue_name_title
```

3. Locally add and commit changes

4. Push the branch to the repo
```
git push -u origin name_of_branch
```

5. In your repo, make sure you are under the correct branch and then click "Open Pull Request"
  --> Add the other 3 members to review the branch

6. Merge!
------------------------------------------------------------------------------------------------------------------------------------------------



![alt text](https://d3i71xaburhd42.cloudfront.net/100dcf6aa83ac559c83518c8a41676b1a3a55fc0/3-Figure1-1.png)


## Anshika Agrawal, Bryan Munoz, Nubaira Milki, Krutal Patel 

In manifold learning one assumes that data given in high-dimensional spaces in fact is on (or concentrated around) a lowdimensional regular set, namely a manifold. Slides with an introduction http://web.cse.ohio-state.edu/mlss09/mlss09_talks/
3.june-WEN/mlss09.pdf.

Theory. You could focus on understanding the motivations, objectives of manifold learning, focus on 2-3 techniques (e.g.
ISOMAP, Local Linear Embeddings, Laplacian eigenmaps/Diffusion maps) explaining the similarities and differences (both in
terms of assumptions, theory and algorithms). Diffusion Maps has been applied in a very large variety of settings beyond
manifold learning, since it can be adapted to dynamical systems (from molecular dynamics (e.g. Determination of reaction
coordinates via locally scaled diffusion map, to single cell trajectories https://www.youtube.com/watch?v=gVAEk2zBf_E)
and to signal processing on graphs (e.g. The Emerging Field of Signal Processing on Graphs).
There are also multiscale techniques called Geometric Wavelets.

Algorithms. Several toolboxes implementing manifold learning algorithms are available, in various languages (Python,
Matlab, R, ...). Discuss the computational complexity of the different algorithms you are considering,

Data Exploration. Trying the algorithms on simple data sets (usually available with the toolboxes themselves), or even
better on some real data set of interest to you (or ask me - these techniques have a really wide range of applicability that
many, many different data sets may be used).

Connections with the course. Multi-Dimensional Scaling; random projections; graphs and networks; Markov chains;
spectral clustering.
