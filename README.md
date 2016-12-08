# SenTenCE: A multi-sensor data compression framework using tensor decompositions for  human activity classification (Work in progress..)
## Abstract:
In this paper, we introduce SenTenCE (Sensor-Tensor Compression Engine), a tensor decomposition based lossy data compression framework for on-phone Inertial Measurement Unit (IMU) sensor data. We show that this technique achieves impressive data compression ratios with acceptably low percent-root mean square distortion that in turn results in negligible change in the classification accuracy of the Deep Convolutional Neural Network (DCNN) based supervised human activity classifier that is trained with the compressed data instead of the raw uncompressed data.

 [[ Original [dataset](http://ps.cs.utwente.nl/Datasets.php "U-Twente dataset").]]


### List of to dos:

1. We would be replicating the work for varying _N<sub>cp</sub>_ and across multiple datasets and deep-net architectures.

2. We also would like to investigate the usage of specialized 2D signal imaging techniques such as 2D-DFT before feeding the sensor matrix
signal into the deep-net classifier. 

3. We are also looking to implement CP decomposition on phone and measure the execution time and power consumption metrics for the compression algorithm. 

4. We also plan to explore disparate tensor decomposition approaches, such as Tucker decomposition and providing comprehensive benchmarking with other approaches such as symbolic representation of time series and piecewise-segmentation based compression.
