# SpectroBearingsCNN
SpectroVibeNet is a convolutional neural network (CNN) designed for classifying vibration-induced spectrograms of damaged bearings, developed as a part of an engineering thesis to aid in predictive maintenance.

Data Transformation in Preprocessing: Vibration signal data from the CWRU Bearing Data Center was converted from MATLAB .mat files into more versatile .csv files for processing.

Spectrogram Generation in Image_processing: Employed Fourier Transform to create spectrograms images from the vibration data, providing a representation of the frequency spectrum over time.

Create and train a CNN in Neural_Network: Suddivise a training dataset into a 70-15-15 percent, utilizing '0 load' condition, and train from scratch a CNN neural network.

Model Evaluation in Test_model: The trained CNN was tested against the test set.
