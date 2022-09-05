# CHB-MIT Seizure Reader
The function openSeizure(file) in seizurereader.py takes a .seizure file as contained in the CHB-MIT EEG seizure dataset and returns data in a legible and useable format.

The function takes a string with the .seizure filepath as an argument and returns an array on the format
[1st seizure start point in seconds,
1st seizure start point in samples,
1st seizure end point in seconds,
1st seizure end point in samples,
...
nth seizure start point in seconds,
nth seizure start point in samples,
nth seizure end point in seconds,
nth seizure end point in samples]

