# K-Means-With-R
Performing cluster analysis using K-Means of Boston Housing dataset.

Steps of doing the analysis:
1. Select the numeric variables that we think are appropriate and useful. Use kmeans and Gaussian Mixture models.
2. Scale the data – using standard scaling or 0-1 minmax scaling. R scale function does standard scaling.
3. Generate the K-means solution. Extract 2-10 k-means clusters using the variable set. Present the Variance-Accounted-For (VAF or R-square).
4. Perform Scree tests to choose appropriate number of k-means clusters
5. Choose 1 K-means solution to retain from the many solutions that we have generated
    a. Use the criteria of VAF.
    b. Interpretability of the segments
    c. For Test, use the centers (means) generated from the training set k-means solution, as the starting point for performing k-means in test. Use VAF and relative cluster sizes as measures of stability.
6. Generate 3-5 Gaussian Mixtures (GM). Remember to start from 50-100 random starts.
7. Choose one solution based on the mean values and interpretation of the generated
mixtures.
8. Compare the chosen k-means training data solution with the chosen GM solution in the
training data from an interpretability perspective.
9. Summarize results.
