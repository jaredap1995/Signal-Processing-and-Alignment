# Signal-Processing-and-Alignment

This repository is dedicated to processing and aligning Electrocardiogram (ECG) signals from multiple sensors in relation to a single reference sensor. The project is currently a work in progress.

## Project Overview
The raw data for this project comes from the study titled "Simultaneous physiological measurements with five devices at different cognitive and physical loads". The dataset is publicly accessible at [PhysioNet](https://physionet.org/content/simultaneous-measurements/1.0.2/). Our goal is to process, filter, and align multiple ECG signals from different sensors for each subject. The ultimate objective is to study respiration indirectly from the ECG data.

## Challenges & Progress
During the initial exploratory phase of the project, I encountered some challenges. For instance, I realized that the initial strategy used to align a single subject's data did not generalize to other subjects. This revelation came during the work detailed in the "Exploratory Label Analysis" notebook. The notebook "Manual Activity Label Generation Single Subject.ipynb" outlines this initial strategy.

Given this discovery, we shifted our focus towards finding an effective way to label data for different activities in the study, for each subject. The approach leveraged both the accelerometer and ECG data. 

The "Labelling Accel Data_Generalizability Test" notebook continues this process, presenting a semi-automated approach to determining activity segments. This approach is based purely on the Accel_Y axis data and signal peaks, provided the number of discrete activity periods is known.

## Future Work
We aim to refine this process further and explore possibilities to automate it completely. Enhancements in the signal processing and alignment methodology would facilitate a more accurate study of respiration patterns, indirectly through ECG signals.

We invite collaboration and suggestions to improve this ongoing work.

## Conclusion
This project promises exciting outcomes, paving the way for efficient ECG signal processing and alignment. With the potential to extract insightful patterns related to respiration, the work done here could open up new avenues in physiological research.
