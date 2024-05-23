The task is to find drone's path on the city map. The map is given in txt and png formats.
We have x_odometry and y_odometry, which shows the drone's movement on the path.
Also there are lidar's measurements in input (list of 36 measurements (each 10 degree angle) for each drone's step on the map).
Lidar's measurements and odometries are noisy and have normal distribution. Lidar's variance is 0.1 and odometries' sensor variance is 4.4.

We should get file with drone's path coordinate in output.
