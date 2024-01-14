# LowPass-Filter-Design-Using-FIR

Filter Design---
FIR filter design for signal processing.

Parameters----
Sample rate: 20,000 Hz
Order: 50
Passband ripple: 1
Stopband attenuation: 50
Passband frequency: 4500 Hz
Stopband frequency: 5000 Hz

Filter Coefficients----
Computed using a windowed sinc function.

Window Function:----
Selection based on passband ripple and stopband attenuation.
Options: rectangular, hanning, hamming, blackman.

Stability Check:----
Pole-zero plot for filter stability.

Response Analysis:----
Frequency, step, and impulse response analysis.

Signal Processing:----
Filtering noisy signal with designed FIR filter.
Signal generation, noise addition.

Audio Processing:----
FIR filter applied to audio file ('tv-glitch-6245.mp3').
Playing original and filtered audio.

Frequency Response Plot:----
Displaying the frequency response of the FIR filter.
