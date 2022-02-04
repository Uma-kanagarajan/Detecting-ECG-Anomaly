# Detecting-ECG-Anomaly

The dataset ECG5000 contains 5000 Electrocardiograms and 140 data points. The dataset has 0 or 1 which represents abnormal rhythm and normal rhythm respectively.

The objective is to train an autoencoder model to detect anomalies.

An autoencoder is trained to minimize reconstruction error. Lets train an autoencoder on the normal rhythms, to reconstruct all the data.

Abnormal rythm will have higher reconstruction error. By fixing a value for threshold, one can classify a rhythm as an anomaly or not.
