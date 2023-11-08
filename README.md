# SpectroBearingsCNN
***Project Overview***
SpectroVibeNet is a convolutional neural network (CNN) designed for classifying vibration-induced spectrograms of damaged bearings, developed as a part of an engineering thesis to aid in predictive maintenance.

**Preprocessing** (Preprocessing file): Transformed the vibration signal data sourced from the CWRU Bearing Data Center by converting .mat files from MATLAB to more flexible .csv formats for subsequent processing steps.
![1png](https://github.com/leonardosos/SpectroBearingsCNN/assets/106916676/6d23d759-d866-46e9-b502-d74700b86490 width='50')

**Spectrogram Creation** (Image_processing file): Fourier Transforms were applied to the vibration data to generate spectrogram images, encapsulating the time-evolving frequency spectrum.
![2](https://github.com/leonardosos/SpectroBearingsCNN/assets/106916676/043ce02c-e33c-4fbb-b80b-30e2cb956000 width='80')

**CNN Development and Training** (Neural_Network file): The training dataset was partitioned in a 70-15-15 split, focusing on the '0 load' condition. A custom CNN was then architected and trained from the ground up.

**CNN Testing** (Test_model file): We conducted an evaluation of the CNN's performance by testing it on a set of data separate from what was used during training.
