(appE)=
# Appendix E - Microphone

The Microphone can be used for a variety of activities with sound waves:

- Demonstrate how the wave pattern changes when frequency and amplitude are changed
- Compare the waveforms from various musical instruments
- Have students capture the waveform of the sound of a tuning fork and model the sine wave using a function
- Measure the speed of sound by using reflected sound waves in a tube
- Demonstrate beat patterns
- Determine the period and then the frequency of a sound by measuring the time between peaks on the waveform
- Display the fast Fourier transform (FFT) of a sound

#### Collecting Data with the Microphone

This sensor is used with the Vernier LabPro® with a computer. Here is the general procedure to follow when using the Microphone:

- 1. Connect the Microphone Probe to the interface.
- 2. Start the data-collection software.

3. The software will identify the Microphone and load a default data-collection setup. You are now ready to collect data.

#### Specifications

Frequency range approximately 20 Hz to 16,000 Hz Maximum frequency LabQuest 10,000 Hz LabPro, SensorDAQ, or CBL 2 5,000 Hz Power 7.5 mA @ 5 VDC Stored calibration Slope 1 Intercept 0 (arbitrary units) **Note**: The maximum data collection rate of the interface affects the maximum frequency you can effectively sample.

#### How the Microphone Works

The Microphone uses an electret microphone that has a frequency response covering essentially the range of the human ear. An op-amp circuit amplifies the signal and sends it to the British Telecom connector. Actually the signal is sent to the interface on two different lines. A signal centered at 2.5 volts is on the Vin-low line and a signal centered at 0 volts is on Vin. More information about the input lines on LabPro a is available in appendix B. The best sound sources to use with the microphone are tuning forks, but you may want to investigate a human voice or a whistle, electronic keyboards, and other musical instruments. Try comparing the wave pattern for different sound sources. Try playing two sounds of nearly the same frequency to produce beat patterns. Make sure the sound level is in the correct range to produce good wave patterns. If the sound is too loud, the wave pattern will be "clipped off" at the top or bottom. Move the microphone further from the sound source, or turn down the volume of the sound.
