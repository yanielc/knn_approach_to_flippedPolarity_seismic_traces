# knn_approach_to_flippedPolarity_seismic_traces
We use a nearest neighbor classifier to search for a type of noise present in modeled seismic data.

There is an imbalance in the class so we upsample the minority class. The upsampling is done such that it does not leak into
the final testing set, nor the validation sets of the cross-validation procedure.

We also show that the standarization is not applicable when all attributes belong to the same type of data.
