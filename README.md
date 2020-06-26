# Autonomous-vehicle-dataset

This dataset consists of about 130 thousand data samples captured at a rate of 10 fps, completing more than 3½ hours of video. The videos are collected at different hours of the day with different weather conditions. Associated with each image of the videos there are 4 parameters: steering wheel angle, accelerator and brake pedal pressures, and vehicle speed. For collecting this data, a human driver drove the vehicle inside the GTA-V game environment. 

This data were collected within the GTA-V “world” map. The circuit chosen is approximately 850 m long and it has several streets where the lane is not delimited. The landscape observed in the route contains vegetation, trees, hills and other elements seen in common real roads, but does not include the presence of other vehicles and pedestrians.

The steering wheel angle, the accelerator and the brake pedal pressures represent relative values varying between zero and one. For the accelerator and brake pedal pressures, zero corresponds to the natural unpressed position. For the steering wheel angle, 0.5 corresponds to the neutral position of the steering wheel, values above 0.5 correspond to clockwise angles and under 0.5 to counterclockwise angles. The vehicle speed is in km/h.

The dataset consists of two zip files: Driver_commands_and_speed.zip and Videos.zip. Each of these zip files contains 36 npy files. These npy files can be read by the numpy command numpy.load('file_name') and each file contains one numpy array. The files with the videos are named XtreinoXX.npy and the files with the driver´s commands and the vehicle speed are named YTreinoXX.npy, where XX is a number varying form 0 to 35. The files XTreinoXX.npy and YTreinoXX.npy with the same number correspondes to a pair video-driver´s commands and speed. The images are in RGB fomat and have 150x240x3 pixels.

The Driver_commands_and_speed.zip file can be download from here and the Videos.zip which is about 9.5 GB can be downloaded from: https://drive.google.com/file/d/1djbcSOMHqWVMDOfoPu2WAzVYV5wI8Eua/view?usp=sharing

This dataset was created by Gustavo Antonio Magera Novello and Henrique Yda Yamamoto in their graduated project: H. Y. Yamamoto and G. A. M. NOVELLO. Autonomous vehicle control with artificial intelligence, Escola Politécnica of University of São Paulo (USP), Mechathronic Engeneering Dept., 2019 (in Portuguese). 
