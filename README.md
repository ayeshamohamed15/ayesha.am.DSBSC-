# DSBSC


EX NO: 2	DSB-SC-AM MODULATOR AND DEMODULATOR

AIM:
To write a program to perform DSBSC modulation and demodulation using SCI LAB and study its spectral characteristics

EQUIPMENTS REQUIRED
•	Computer with i3 Processor
•	SCI LAB

Note: Keep all the switch faults in off position

Algorithm:
1.	Define Parameters:
•	Fs: Sampling frequency.
•	T: Duration of the signal.
•	Fc: Carrier frequency.
•	Fm: Frequency of the message signal.
•	Amplitude: Maximum amplitude of the message signal.
2.	Generate Signals:
•	Message Signal: A sinusoidal signal that will be modulated.
•	Carrier Signal: A high-frequency sinusoidal signal used for modulation.
3.	DSBSC Modulation:
•	Modulated Signal: Multiply the message signal by the carrier signal to produce the DSBSC signal.
4.	DSBSC Demodulation:
•	Multiplication: Multiply the modulated signal by the carrier signal to get the product of the message signal with itself (i.e., the original message signal plus high-frequency components).
•	Low-pass Filtering: Apply a Butterworth low-pass filter to remove the high- frequency components and recover the original message signal.
5.	Visualization:
Plot the message signal, carrier signal, DSBSC modulated signal, and the recovered signal after demodulation.

PROCEDURE
•	Refer Algorithms and write code for the experiment.
•	Open SCILAB in System
•	Type your code in New Editor
•	Save the file
•	Execute the code
•	If any Error, correct it in code and execute again
•	Verify the generated waveform using Tabulation and Model Waveform

Model Waveform

<img width="703" height="679" alt="image" src="https://github.com/user-attachments/assets/e7c7c7f8-ccf2-41ac-b1f3-325989941a6f" />

Program

<img width="466" height="629" alt="image" src="https://github.com/user-attachments/assets/9abc3066-c4c0-42e3-8171-a9a608f35aed" />

Output Graph

<img width="1919" height="898" alt="image" src="https://github.com/user-attachments/assets/44bf8b7c-7e45-4a85-a0cd-e6ebb31e32b5" />

Tablular Column

![WhatsApp Image 2025-09-23 at 20 06 46_28b81b6f](https://github.com/user-attachments/assets/49e8db72-a32f-4b76-a6a5-f56ebfceb2e3)

Result

Thus the DSB-SC-AM Modulation and Demodulation is generated.

