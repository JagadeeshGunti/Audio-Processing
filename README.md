# Audio-Processing
Python program analyzes songs, reading audio files and generating spectra. Utilizes NumPy, SciPy, and Matplotlib for visualizing frequency components.
Audio Input: The program accepts a song file as input, supporting formats like MP3 or WAV.

Signal Processing: Utilizing NumPy and SciPy, the program reads the audio file, extracts the audio signal, and performs necessary preprocessing, such as resampling or filtering.

Fast Fourier Transform (FFT): The core of the spectrum analysis involves applying the FFT algorithm to convert the audio signal from the time domain to the frequency domain. This transformation reveals the frequency components present in the audio.

Visualization: Matplotlib is employed to create a graphical representation of the spectrum. The x-axis corresponds to different frequencies, while the y-axis represents the amplitude or energy at each frequency.

User Interaction: Users can specify the path to the song file within the program. The resulting spectrum is then displayed, providing insights into the song's frequency distribution.

Optional Features: Additional features may include the ability to customize the analysis window, adjust parameters like sampling rate, and explore different color mappings for the spectrum plot.
![image](https://github.com/JagadeeshGunti/Audio-Processing/assets/144555870/1712aa2b-fe6f-487e-9237-50687e55bba3)
