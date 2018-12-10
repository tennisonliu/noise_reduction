# noise_reduction
Using Spectral Noise Gating (SNG) techniques to reduce background noise in streaming microphone input for enhanced vocal recognition

Noise reduction algorithm written in Python based on Spectral Noise Gating (SNG) technique used by audio editing software (e.g. Audacity, Adobe Audition).

For more on how SNG noise reduction works, read https://wiki.audacityteam.org/wiki/How_Audacity_Noise_Reduction_Works

The python script was written in Jupyter Notebook and certain functionalities will only work in the notebook.

# Requirements
Python Modules required:
1. IPython
2. scipy
3. numpy
4. librosa

# How to use
Pass two wav files into the script:
* An audio clip of the noise signal
* An audio clip of the audio recording with the additive noise signal included.
