 Floorplan-Reconstruction-Dataset
 ====
**1.**  This dataset contains LiDAR data from 6 sequences as well as CAD ground truth. The data collection occurred in an indoor roughcast structural environment, thus the scene was relatively tidy and free of unnecessary objects. Additionally, the CAD data also corresponded to the  roughcast environment.

![equipment](https://github.com/David2liu/Floorplan-Reconstruction-Dataset/blob/main/equipment.jpg "equipment") 

**2.** The dataset employs MID360 and an integrated IMU for data collection. The extrinsic parameters of the LiDAR and IMU, as well as the intrinsic parameters of the IMU itself, can be referenced in the Mid360 manual.


**3.** The dataset is categorized into three series: easy, middle, and hard. Each category corresponds to varying scene sizes and complexities.

**4.** The Mid360 LiDAR has been installed on the Unitree Go2 to facilitate data collection. The LiDAR and the ground are inclined at a tilt angle of $13^\circ$, consequently, the input point cloud is adjusted to align with the gravitational direction through transformation.
