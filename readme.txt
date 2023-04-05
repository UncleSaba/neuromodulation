Santeri Pöllänen
2022
santeri.pollanen@gmail.com

This package contains the core of the code necessary to reproduce the results presented in my Master's thesis "Dynamical neuromodulation with pulse waveforms in a brain circuit model". The dataset this is written for is the Speech Commands data set (Warden P. 2018. Speech commands: A dataset for limited-vocabulary speech recognition). The data set is not included here due to its size being in the dozens of gigabytes.

The preprocessing folder contains the code I used to process the wav audio files into gammatone representations. The gammatone representations are then employed in the model training and evaluation code in the training folder. The modulation and visualization are contained in the notebook in the modulation folder. The work done with detecting rising and falling edges in the audio to find correlations between sound onset and classification accuracy is contained in the edge_detection folder.
