**Path Loss Evaluation Data Set (PLChannelinputs.csv)**

1st Row : Sunload Sensor Values ([33 (dark-no light) , 475 (bright sun)] mV ) \
2nd Row : Receiver Vehicle Occupied Lane, (0: same lane leader-follower, 1: left nearby lane , 2: right nearby lane, 3: right nearby lane-curvy road) \
3rd Row: Optical Receiver Inclination Angle [0 Degree : LoS , 30 Degree DLoS ] \
4th Row:  Inter-vehicle Distance [m] \
5th Row: Optical Turbulence (0: low turbulence, 1:high turbulence)


**Path Loss Validation Data Set (valPLdata.csv)**

1st Row : Sunload Sensor Values ([33 (dark-no light) , 475 (bright sun)] mV ) \
2nd Row : Receiver Vehicle Occupied Lane, (0: same lane leader-follower, 1: left nearby lane , 2: right nearby lane, 3: right nearby lane-curvy road) \
3rd Row: Optical Receiver Inclination Angle [0 Degree : LoS , 30 Degree DLoS ] \
4th Row:  Inter-vehicle Distance [m]\
5th Row: Optical Turbulence (0: low turbulence, 1:high turbulence)\
6th Row: Measured Path Loss [dB] = Target Value


**Raw Path Loss Data Set (rawPLdataset.csv)**

1st Column : Measurement Location Longitude \
2nd Column : Measurement Location Latitude  \
3rd Column: RSS [dBm] \
4th Column: Measurement Time\
5th Column : Accelerometer X Axis (used for data cleaning)\
6th Column: Accelerometer Y Axis (used for data cleaning) \
7th Column: Accelerometer Z Axis (used for data cleaning) Measured Path Loss [dB] \
8th Column: Sunload Sensor Values ([33 (dark-no light) , 475 (bright sun)] mV ) \
9th Column : Receiver Vehicle Occupied Lane, (0: same lane leader-follower, 1: left nearby lane , 2: right nearby lane, 3: right nearby lane-curvy road) \
10th Column : Optical Receiver Inclination Angle [0 Degree : LoS , 30 Degree DLoS ] \
11th Column : Inter-vehicle Distance [m] \
12th Column : Optical Turbulence due to Exhaust Plumes (0: low turbulence, 1:high turbulence) \
13th Column : Transmit Power [dBm]\
14th Column : Path Loss [dB]
