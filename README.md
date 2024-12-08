# Morse Code Translator Using an IIR Filter
This is a Morse code translation program that works using Pyfirmata, using sampled audio data from an Arduino uno and processes it using bandpass IIR filtering.
For this version of Morse code translation a dot is defined as a 200Hz signal of length 0.2 seconds and a dash
is defined as a 400hz signal with length 0.2 seconds.

## Installation

Install required packages as follows:

```bash
pip install py-iir-filter
```

## Arduino Initialisation

Flash Ardunio Uno with the StandardFirmata.ino

## Set up Circuit

Any microphone set up can be used, as long as it is compatible with the Arduino Uno and the output is connected to the analogue pin 0 on the Arduino Uno.
An example circuit is shown below and how to connect it:

![Pre-Amplifier Circuit](circuit.svg)

## Running Program
First run IIR.py to run unit test
Then program can then be ran by running the main.py file from the terminal.



