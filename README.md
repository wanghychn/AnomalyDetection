# An Unsupervised Framework for Anomaly Detection in a Water Treatment System 
Current Cyber-Physical Systems (CPSs) are sophisticated, complex, and equipped with networked sensors and actuators. As such, they have become further exposed to cyberattacks. Recent catastrophic events have demonstrated that standard, human-based management of anomaly detection in complex systems is not efficient enough and have underlined the significance of automated detection, intelligent and rapid response. Nevertheless, existing anomaly detection frameworks usually are not capable of dealing with the dynamic and complicated nature of the CPSs. In this study, we introduce an unsupervised framework for anomaly detection based on an Attention-based Spatio-Temporal Autoencoder. In particular, we first construct statistical correlation matrices to characterize the system status across different time steps. Next, a 2D convolutional encoder is employed to encode the patterns of the correlation matrices, whereas an Attention-based Convolutional LSTM Encoder-Decoder (ConvLSTM-ED) is used to capture the temporal dependencies. More precisely, we introduce an input attention mechanism to adaptively select the most significant input features at each time step. Finally, the 2D convolutional decoder reconstructs the correlation matrices. The differences between the reconstructed correlation matrices and the original ones are used as indicators of anomalies. Extensive experimental analysis on data collected from all six stages of Secure Water Treatment (SWaT) testbed, a scaled-down version of a real-world industrial water treatment plant, demonstrates that the proposed model outperforms the state-of-the-art baseline techniques.
