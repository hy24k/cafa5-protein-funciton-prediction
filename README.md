This repo walks through on how to train a DNN model using TensorFlow on the CAFA 5 protein function Prediction dataset made available for this competition.

The objective of the model is to predict the function(aka GO term ID) of a set of proteins based on their amino acid sequences and other data.

> Note : This notebook runs without any GPU. This is because enabling GPUs leaves less RAM memory on the VM and the submission step needs a lot of memory. One point where this would impact is when training the model. With CPU it will take around 2 minutes while on GPU it would take around 30 seconds.
