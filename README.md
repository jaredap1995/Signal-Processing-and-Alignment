# Signal-Processing-and-Alignment
Processing ECG signals and aligning multiple sensors according to a single reference sensor (work in progress)

This project is working with the raw data from "Simultaneous physiological measurements with five devices at different cognitive and physical loads" (available from https://physionet.org/content/simultaneous-measurements/1.0.2/) attempting to process, filter, and align the multiple ECG signals from various sensors for each subject to ultimately study respiration indirectly from ECG.

In the "Exploratory Label Analysis" file I discover that that my initial strategy I used to align a single subject (found in "Manual Activity Label Generation Single Subject.ipynb") does not generalize to other subjects. So I shift most of my energy to finding a good way to label the data for the different actvities in the study for each subject by combinging the accelerometer and ECG data. This process is continued in "Exploratory Label Analysis 2."  
