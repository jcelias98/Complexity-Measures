# Complexity-Measures
Implementation in Python of a set of measures to characterize the complexity of classification problems based on aspects that quantify the linearity of the data, the presence of informative feature, the sparsity and dimensionality of the datasets. The measures were originally proposed by Ho and Basu [1] and extend by many other works including the ECoL library.

### Feature-based Measures
- Maximum Fisher’s Discriminant Ratio (F1)
- The Directional-vector Maximum Fisher’s Discriminant Ratio (F1v)
- Volume of Overlapping Region (F2)
- Maximum Individual Feature Efficiency (F3)
- Collective Feature Efficiency (F4)
### Neighborhood Measures
- Fraction of Borderline Points (N1)
- Ratio of Intra/Extra Class Nearest Neighbor Distance (N2)
- Error Rate of the Nearest Neighbor Classifier (N3)
- Non-Linearity of the Nearest Neighbor Classifier (N4)
- Fraction of Hyperspheres Covering Data (T1)
- Local Set Average Cardinality (LSC)
### Dimensionality Measures
- Average number of features per dimension (T2)
- Average number of PCA dimensions per points (T3)
- Ratio of the PCA Dimension to the Original Dimension (T4)
