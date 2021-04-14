# Prediction-of-PGA-PGV-and-5-Damped-PSA-for-PEER-NGA-West2-database-using-RSO-DNN

The codes show how to predict PGA,PGV and 5% damped PSA under a specific source, path and site condition using a refined second-order deep neural network.

The codes are developed based on Python with Tensorflow and the description of the codes are as follows:

1. Generate_RSODNN.py: This code is for generating the refined second-order deep neural network (RSO-DNN) model for predicting PGA,PGV, and 5% damped PSA under a specific source, path, and site condition. This is the raw model so that one can freely modify the architecture or training method to get his/her own model.

2. Simple_example.py: This code can produce the attenuation relationship under a specific source, path and site condition which was described in the csv file 'PGA_R.csv' . One can easily run this code by editing this csv file.

3. PGA_R.csv: This file provides the source, path, and site condition for the prediction in 'Simple_example.py'.The parameter from the first column to the last column means Fault Type, Ztor, M, RJB, Region, Vs30, z1 and T respectivly.
