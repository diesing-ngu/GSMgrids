## GSMgrids

Workflow to spatially predict the content of mud (silt and clay) of seafloor surface sediments in Norway, based on measured grain-size data and predictor variables.

### Main characteristics

Variable pre-selection with Boruta algorithm (Kursa & Rudnicki, 2010) and de-correlation analysis.

Spatial predictions with Random Forest (Breiman, 2001) including spatial 10-fold cross validation and model tuning (mtry and final variable selection with forward feature selection).

Estimation of the area of applicability of the model (Meyer & Pebesma, 2021).

### References

Breiman, L. (2001). Random Forests. Machine Learning, 45, 5–32.

Kursa, M., & Rudnicki, W. (2010). Feature selection with the Boruta Package. Journal of Statistical Software, 36(11), 1–11. http://www.jstatsoft.org/v36/i11/paper/

Meyer, H., & Pebesma, E. (2021). Predicting into unknown space? Estimating the area of applicability of spatial prediction models. Methods in Ecology and Evolution, 12(9), 1620–1633. https://doi.org/https://doi.org/10.1111/2041-210X.13650
