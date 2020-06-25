# Autonomous-vehicle-dataset

This dataset consists of about 130 thousand data samples captured at a rate of 10 fps, completing more than 3½ hours of video. The videos are collected at different hours of the day with different weather conditions. Associated with each image of the videos there are 4 parameters: steering wheel angle, accelerator and brake pedal pressures, and vehicle speed. For collecting this data, a human driver drove the vehicle inside the GTA-V game environment. 

This data were collected within the GTA-V “world” map. The circuit chosen is approximately 850 m long and it has several streets where the lane is not delimited. The landscape observed in the route contains vegetation, trees, hills and other elements seen in common real roads, but does not include the presence of other vehicles and pedestrians.

The steering wheel angle, the accelerator and the brake pedal pressures represent relative values varying between zero and one. For the accelerator and brake pedal pressures, zero corresponds to the natural unpressed position. For the steering wheel angle, 0.5 corresponds to the neutral position of the steering wheel, values above 0.5 correspond to clockwise angles and under 0.5 to counterclockwise angles. The vehicle speed is in km/h.

The dataset consists in two zip files: Driver_commands_and_speed.zip and Videos.zip. Each of these zip files contains 36 npy files, with numpy arrays. The files with the videos, in the Videos.zip, are named XtreinoXX.npy and the files with the driver´s commands and the vehicle speed, in the Driver_commands_and_speed, are named YTreinoXX.npy, where XX is a number varying form 0 to 35. The files XTreinoXX.npy and YTreinoXX.npy with the same number correspondes to a pair video-driver´s commands and speed. The imagens are in RGB fomat and have 150x240x3 pixels.

The Driver_commands_and_speed.zip can be download from here and because the Videos.zip is too large it can be downloaded from
