# isw

This is a data repository containing the power spectra and covariance matrices used in the RACS ISW analysis. All files can be opened using numpy.load. 
The galaxy and ISW power spectra can be accessed with the keywords 'cl_gal' and 'cl_isw' respectively. We use 'cov_ggisw' for the precision matrices. 
MLE_precision_matrices_3000_binwidth_20.npz contains the precision matrix obtained from inverting the sample covariance, whereas 
GLASSO_precision_matrices_3000_binwidth_20.npz has been estimated using the graphical lasso approach.
