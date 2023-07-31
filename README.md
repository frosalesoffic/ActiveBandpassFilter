# ActiveBandpassFilter
Create an Active Bandpass Filter using Ltspice
  
  The primary purpose of “filters” in electronic circuits is to supress the undesired
signals or interference. It may be that it is required to remove high-frequency
noise (low-pass filter) or to eliminate 120 Hz ac line interference (high-pass-
filter), or to select a signal in a given frequency band (bandpass filter), etc.

  As indicated earlier, a filter’s primary purpose is to differentiate among different
bands of frequencies, and therefore frequency selectivity is the most common
method of classifying filters. Names such as lowpass, highpass, bandpass, and
bandstop are used to categorize filters, but it takes more than a name to
completely describe a filter.


  The frequency specifications used to describe the passband(s) and
stopband(s) could be provided in hertz (Hz) or in radians/second (rad/sec). We
will use the frequency variable f measured in hertz as filter input and output
specifications because it is a slightly more common way of discussing frequency.
However, the frequency variable ω measured in radians/second will also be used
as a variable of choice for unnormalized frequency responses since most of those
calculations will use radians/second.

  The other major filter specifications are the gain characteristics (see (2)) of
the passband(s) and stopband(s) of the filter response. A filter's gain is simply the
ratio of the output signal level to the input signal level. If the filter's gain is
greater than 1, then the output signal is larger than the input signal, while if the
gain is less than 1, the output is smaller than the input. In most filter
applications, the gain response in the stopband is very small. For this reason,
the gain is typically converted to decibels (dB):
Gain dB = 20 log(Gain)
