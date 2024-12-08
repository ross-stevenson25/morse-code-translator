# Morse Code Translator Using an IIR Filter
This is a Morse code translation program that works using Pyfirmata, using sampled audio data from an Arduino uno and processes it using bandpass IIR filtering.
For this version of Morse code translation a dot is defined as a 200Hz signal of length 0.2 seconds and a dash
is defined as a 400hz signal with length 0.2 seconds.

## Installation

Install required packages as follows:

```bash
pip install py-iir-filter
```

