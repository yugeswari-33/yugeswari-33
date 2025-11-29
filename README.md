
**yugeswari-33/yugeswari-33** 
Implementing K-Means Clustering from Scratch and Evaluating Performance:
Description:
The code implements K-Means clustering, an unsupervised learning algorithm, from scratch using NumPy. It partitions the data into K clusters by minimizing the within-cluster sum of squares (inertia). The code also tracks the evolution of inertia across iterations to show convergence.
Methodology:
1. Initialization:
    - Choose K random points from the dataset as initial centroids.

2. Assignment Step:
    - Calculate the distance of each point to every centroid.
    - Assign each point to the cluster with the nearest centroid.

3. Update Step:
    - Compute new centroids by calculating the mean of all points assigned to each cluster.

4. Convergence Check:
    - Repeat assignment and update steps until centroids no longer change or max iterations are reached.
    - Track inertia at each iteration to monitor convergence.

5. Output:
    - Final cluster labels and centroids.
    - Plot evolution of inertia to show performance across iterations.
