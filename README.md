

If you are using this dataset in your personal work, please acknowledge us in your publication(s) by referring to: 

@inproceedings{jomrich2019map_change_detection, author = {Jomrich, Florian and Bischoff, Daniel and Knapp, Steffen and Meuser, Tobias and Richerzhagen, B{"{o}}rn and Steinmetz, Ralf}, booktitle = {In Proceedings of the International Conference on Vehicle Technology and Intelligent Transport Systems (VEHITS)}, title = {{Lane Accurate Detection of Map Changes
based on Low Cost Smartphone Data}}, year = {2019}, month = {May}, location = {Heraklion, Crete, Greece} }



Specification of the files: 

day_individual_runs: 
Provides folders with the per day runs executed for the data set
The GNSS information is stored in the gpssensed.csv file. The accsensed.csv contains further the correlating accelerometer data - to detect lane changes. 

In the gpssensed.csv - "annotation" -> the manually annotated lane changes or start and end of a construction side
"lane annotation" -> the annotation of a lane change induced by algorithmic detection (based on accelerometer and gyroscope readings).


full_data_set: 
Contains all the collected GNSS data in one single csv files

only_right_lane_data_on_a60_highway:
Contains only GNSS data that was recorded