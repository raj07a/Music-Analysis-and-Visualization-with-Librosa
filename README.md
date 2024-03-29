Music Analysis and Visualization with Librosa
This repository contains Python code for analyzing and visualizing music using the Librosa library. Librosa is a powerful tool for audio analysis and processing in Python, commonly used for tasks such as feature extraction, tempo estimation, beat tracking, and more.

Features
Loading Audio: Load an audio file (e.g., MP3) using Librosa's librosa.load() function.
Mel Spectrogram: Compute the Mel spectrogram of the audio signal using librosa.feature.melspectrogram() and visualize it.
Chromagram: Compute the chromagram of the audio signal using librosa.feature.chroma_stft() and visualize it.
Onset Detection: Compute the onset strength envelope of the audio signal using librosa.onset.onset_strength().
Tempo Estimation: Estimate the tempo (beats per minute) of the audio signal using librosa.beat.tempo() and librosa.beat.beat_track().
Harmonic-Percussive Source Separation (HPSS): Separate the audio signal into its harmonic and percussive components using librosa.effects.hpss().
Requirements
Python 3.x
Librosa
Numpy
Matplotlib
IPython
