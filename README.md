# CustomerChurnPredictionRFM

Here, the model is based on how loyal the customers are so that we can strategise our marketing and discounting finances.
The customer segmentaion is done on the basis of RFM (R - "Recency", F - "Frequency", M - "Monetary") values and clusters.

The RFM values needs to be scaled for training so have scaled here wth log transformations.
 
 After that the data is feeded into the Kmeans algorithm and is fitted to it.
 
 AFter Fitting, the values of clusters are predicted and customers are clssified.
