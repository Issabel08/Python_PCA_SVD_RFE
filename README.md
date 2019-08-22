# Python_PCA_SVD_RFE
Example of dimensionality reduction, comparing PCA versus SVD, like a plus: RFE (Feature ranking with recursive feature elimination)

Results:

 	                PCA 	TruncatedSVD 	RFE
data_processing 			
	        None 	0.917622 	0.917314 	0.919317
StandardScaler 	0.949054 	0.954379 	0.964937


Conclusions:
Like we can see above, generally the best results are using StandardScaler.
RFE has the best results for this example of dimensionality reduction.
