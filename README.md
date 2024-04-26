# Quantum K-Means Clustering

This repository implements the K-means clustering algorithm using quantum state encoding for classical data points and encodes them to Quantum.

## ⚛️ Functions

1. `generate_random_data`: Generates a NumPy array of random data with one column <Ket>.
   
2. `ground_state`: Returns a NumPy array representing the ground state (|0> state).
   
3. `initialize_centroids`: Randomly initializes k centroids from the data points.
   
4. `encode_data`: Encodes classical data points into quantum states using an RXGate.
   
5. `findClosestCentroids`: Computes the centroid memberships for every encoded data point.
   
6. `computeCentroids`: Returns the new centroids by computing the means of the data points assigned to each centroid.
   
7. `K_means_Quantum_clustering`: Performs K-means clustering on classical data points using quantum state encoding.
