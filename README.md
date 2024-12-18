# Audio-Synthesizer
An **audio synthesizer** program that enables the user to adjust the **properties** of the generated sound. 

The controls provided by a synthesizer depend on the kind of applications the synthesizer is designed for. While some synthesizer controls are used adjust the most basic physical properties of the generated sound output, namely, the amplitude (which determines the loudness or intensity) and the pitch (the audio frequency, which determines how shrill the generated sound is), others serve more sophisticated purposes such as changing the resonant frequency of the low-pass filter through which the input signal is passed. 

<p align="center">
  <img src="https://github.com/user-attachments/assets/294158f6-fcad-4dc5-b34b-822dea192e4b" />
</p>

### **Installation**

- Log into MATLAB
- Go to MATLAB Drive, upload 'Audio_Synthesizer.mlappinstall'
- Go to MATLAB, under "APPS" tab, click "Install App"
- Select "Audio_Synthesizer" from the MATLAB Drive
- Install dependencies such as DSP System toolbox is prompted
- Run the installed App "ECE 45 Synthesizer Project"

### **Properties**

**Envelopes:** a table of data points that is output over a specified period of time.
An x-y plot that shows how any given attribute of the output signal (such as pitch) should evolveover time. 
Envelopes enable a synthesizer to change sound characteristics **automatically** over time, unlike sliders that need to be varied manually.

**Four Stages of an envelope:** attack, decay, sustain, and release.

**Attack:** the synthesizer tunes up the desired sound attribute (the quantity plotted along the y-axis, say amplitude) to a peak value.

**Decay:** the quantity is made to decrease untilit hits a certain user-defined value.

**Sustain:** sustains the amplitude at the user-defined value resulting from the decay stage.

**Release:** allows the quantity fade out until its value reaches 0.

<p align="center">
  <img src="https://github.com/Unforgiven6/Audio-Synthesizer/assets/80782918/1cc244e9-f6f5-4a32-8e28-fe724a4f97ec" />
</p>

**Plan:** Using MATLAB, write a code to design a synthesizer. Choose an oscillator waveform and add to it a linear filter with adjustable parameters to obtain different sounds.

## **Procedures**

**Set Up MATLAB Environment:**
Ensure MATLAB is installed on the system. If not, download and install it from MathWorks' official website. Familiarize with basic MATLAB syntax and functionalities if haven't already.

**Research and Plan:**
Review the prompt and gather information about different oscillator waveforms, filters, modulation techniques, and other features to be implemented in the synthesizer. Plan out the structure of the code and the user interface layout.

**Implement Oscillator and Filter:**
Start by coding an oscillator function that generates waveforms such as sine, square, triangle, or sawtooth waves. Then, implement a linear filter function with adjustable parameters like cutoff frequency, resonance, and filter type (low-pass, high-pass, band-pass, etc.).

**Add Noise and Modulation:**
Incorporate noise generation functions and modulation techniques such as Low-Frequency Oscillators (LFOs) to modulate parameters like pitch, filter cutoff, or oscillator frequency. Use functions like randn() to generate Gaussian noise and create LFOs using sinusoidal or other periodic signals.

**Design User Interface (UI):**
Use MATLAB's GUI development tools like App Designer or GUIDE to create a user-friendly interface for the synthesizer. Include sliders, knobs, buttons, and displays to control parameters and visualize the generated sounds.

**Implement Additional Features:**
Add extra features like pitch modulation, envelope generators, effects (reverb, delay, distortion), and preset management.

**Testing and Debugging:**
Test each component of the synthesizer individually to ensure they work as expected. Debug any errors or unexpected behavior.

**Document and Report:**
Write a comprehensive report that covers the following:

1. Potential applications of your synthesizer.
2. Detailed description of all synthesizer controls.
3. Explanation of the applied concepts from your class.
4. Proper citation of borrowed code and functions.
5. Contributors credit.

**Finalize and Share:**
Once satisfied with the synthesizer and documentation, finalize the project and share it with peers or instructor for feedback.
