# rfi-matlab
FIR Filter Design using Uniform Frequency Sampling Method
This project implements an FIR (Finite Impulse Response) filter design in MATLAB using the uniform frequency sampling method via the built-in fir2 function. The application features a user-friendly graphical user interface (GUI) to configure and visualize the filter parameters and response.

* Main Functionalities:

Filter Order: Adjustable via slider or numeric input.

Frequency Bands [Hz]: Customizable vector specifying passband and stopband edges.

Filter Gain: Editable vector defining desired gains at specified frequency points.

Sampling Frequency [Hz]: User-defined through text input.

Window Type: Selectable from Rectangular, Hamming, Hann, Bartlett, or Blackman via Radio Button Group or dropdown menu.

* Visualization Outputs:

The GUI displays separate plots for:

Filter coefficients

Zeros of the filter

Amplitude and phase characteristics (normalized frequency and radian frequency)

Amplitude characteristics in decibels (non-normalized frequency)

* Bonus Features:

Ideal filter response is plotted alongside the designed filter response, highlighting cutoff frequencies and ripple levels.

Ability to switch amplitude-frequency representation between normalized frequency, normalized radian frequency, and non-normalized frequency (Hz).

Separate GUI interfaces for:

Applying a chirp signal (0 Hz to Fs/2, 1-second duration) to the designed filter and visualizing input/output signals and spectrograms.

Importing an audio file, filtering the audio, and displaying the filtered signal spectrogram.
