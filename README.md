# Linear Voltage Function Generator

This was the project I worked on during my time at Toronto Metropolitan University (formerly Ryerson University), where we were given a set of parameters and IC's (integrated circuits).
This project includes 4 parts in order to build a working linear voltage function generator:
1. I designed and built a inverting amplifier that cascades with a non-inverting bistable Op-Amps (Operational Amplifiers) or more specifically LM741CN IC's. The output of the invertiing amplifier op-amp produces the triangular waveform, where the output of non-inverting bistable op-amp produces the square waveform.
2. The next part, I used 1N4148 and 1N4734A diodes to design a voltage limiter to limit the voltage output our circuit.
3. This part, I implemented another inverting bistable op-amp that is then connected to a DC to +-DC converter which is made up of a 1N4148 diode and a 2N3904 transistor. This allows the user to control the frequency of this circuit by varying its input voltage between 0V to 5V.
4. This last step I took the outputs of the frequency generator and connected them to a potentiometer, which is then connected to an op-amp buffer circuit. This allows the user to vary the amplitude of the waveforms by turning the knob on the potentiometer which changes the resistance going through the buffer.

Following these guidelines, I was able to design and develop a Linear Voltage Function Generator that allows the user to switch between triangular waveforms and square waveforms, as well as allowing its user to control its frequency and amplitude.
<!--
<img src="https://github.com/user-attachments/assets/bc800d42-9adb-4809-be05-e38c3c93ba8e" alt="Project 2" style="width:30%; height:auto;">
![image(1)](https://github.com/user-attachments/assets/f880b5e6-2788-4496-b092-7125fbbaed09)
![image(2)](https://github.com/user-attachments/assets/6273ce74-02b9-4fa0-beaa-7033ea060721)
![image(3)](https://github.com/user-attachments/assets/314c030d-0c0a-4a4a-beb4-09ce89c00d66)
![image(4)](https://github.com/user-attachments/assets/be20855d-7166-431e-89bf-32c3756bcbcc)
![image(5)](https://github.com/user-attachments/assets/8422ddc5-5532-44f9-9815-91e6bd85c082)
![image](https://github.com/user-attachments/assets/51b997f4-8c57-42fc-bdbe-be575b2d8972)
-->

## The Theoretical circuit design with expected waveforms.
<img src="https://github.com/user-attachments/assets/51b997f4-8c57-42fc-bdbe-be575b2d8972" alt="Theoretical" style="width:60%; height:auto;">

## The Theoretical circuit design completed on NI Multisim.
<img src="https://github.com/user-attachments/assets/f880b5e6-2788-4496-b092-7125fbbaed09" alt="Multisim" style="width:60%; height:auto;">

## The Theoretical waveform using the NI Multisim software.
<img src="https://github.com/user-attachments/assets/8422ddc5-5532-44f9-9815-91e6bd85c082" alt="Multisim" style="width:60%; height:auto;">

## The Actual Build of the designed circuit on a breadboard.
<img src="https://github.com/user-attachments/assets/6273ce74-02b9-4fa0-beaa-7033ea060721" alt="Multisim" style="width:60%; height:auto;">

## The expected Triangualr waveform read through an oscilloscope.
<img src="https://github.com/user-attachments/assets/314c030d-0c0a-4a4a-beb4-09ce89c00d66" alt="Multisim" style="width:60%; height:auto;">

## The expected Square waveform read through an oscilloscope.
<img src="https://github.com/user-attachments/assets/be20855d-7166-431e-89bf-32c3756bcbcc" alt="Multisim" style="width:60%; height:auto;">
