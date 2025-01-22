**Audio Analysis Script using Librosa**
This script analyzes audio files in a specified folder, providing insights into various aspects of the audio data, 
such as duration, waveform visualization, and audio features (e.g., RMS Energy, Zero-Crossing Rate, MFCCs, and Pitch). 
It also visualizes distributions of these features using histograms.

**Features**
1. File Processing
Counts the number of .wav files in a specified folder.
Displays a list of all .wav file paths.
2. Waveform Visualization
Loads and displays the waveform of selected .wav files using librosa.display.waveshow.
3. Duration Analysis
Calculates the total, average, minimum, and maximum durations of the audio files.
Visualizes the distribution of durations with a histogram.
4. Audio Playback
Allows playback of specific audio files using IPython.display.Audio.
5. Audio Feature Extraction
RMS Energy: Computes the root-mean-square energy for each audio file.
Zero-Crossing Rate: Calculates the rate at which the waveform crosses the zero line.
MFCCs: Extracts Mel Frequency Cepstral Coefficients (MFCCs) and visualizes their distribution.
Pitch (Fundamental Frequency): Calculates the pitch and its distribution across files.
6. Visualizations
Waveform plots for individual audio files.

**Histograms for distributions of**:
Audio file durations
RMS Energy values
MFCC values

**Requirements**
Make sure the following libraries are installed before running the script:

librosa
matplotlib
IPython
numpy
