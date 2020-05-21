# DeLTA2020
ML Code-International Conference on Deep Learning Theory and Applications (DeLTA) 2020

Multi-Channel ConvNet Approach to Predict the Risk of In-Hospital Mortality for ICU Patients

Fabien Viton, Mahmoud Elbattah, Jean-Luc Guérin, Gilles Dequen

Abstract:	The healthcare arena has been undergoing impressive transformations thanks to advances in the capacity to capture, store, process, and learn from data. This paper re-visits the problem of predicting the risk of in-hospital mortality based on Time Series (TS) records emanating from ICU monitoring devices. The problem basically represents an application of multi-variate TS classification. Our approach is based on utilizing multiple channels of Convolutional Neural Networks (ConvNets) in parallel. The key idea is to disaggregate multi-variate TS into separate channels, where a ConvNet is used to extract features from each univariate TS individually. Subsequently, the features extracted are concatenated altogether into a single vector that can be fed into a standard MLP classification module. The approach was experimented using a dataset extracted from the MIMIC-III database, which included about 13K ICU-related records. Our experimental results show a promising accuracy of classification that is competitive to the state-of-the-art. 
