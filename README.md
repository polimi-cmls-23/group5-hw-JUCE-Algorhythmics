# Analysis of a JUCE Plugin - NEL-19
Analysis of plugin NEL-19 https://github.com/Mrugalla/NEL-19

The aim of the NEL-19 plugin is to develop a vibrato effect based on re-sampling, using a feed-forward delay to modulate the input signal.
The user has the possibility to create several types of vibrato texture by selecting from seven modulators with different functionalities.

<div>
<img width="500px" src="gui.png">
<div>

# Block Diagram
This plugin adds more useful elements than a simple vibrato. There is a
Feedback, filtered by a Lowpass Filter, that is commonly use in effects
like Flanger and Phaser to determinate the amount of output signal that falls into the circuit.
In addition, the Delay is modulated by a mix (Mods Mix) of different modulators (Modulators), that
the user can select to create different effects.
To create the output signal, there is a mix between dry and wet signals (Mix).

<div>
<img width="300px" src="nel19.drawio.png">
<div>
 
# Modulators
There are seven modulators to create different effects.
* Perlin Noise
* Audio-Rate
* Dropout
* Envelope Follower
* Macro
* Pitch Band
* LFO
  
# Group: Algorhythmics 
* Alice Sironi
* Cecilia Raho
* Stefano Ravasi
* Yan Zhuang
