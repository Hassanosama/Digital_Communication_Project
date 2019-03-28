# Digital_Communication_Project
Simulate the performance of different modulation schemes, BPSK, QPSK, FSK, QAM(16-64) in an AWGN environment.

**BPSK**

BPSK is a two phase modulation scheme, where the 0’s and 1’s in a binary message are represented by two different phase states in the carrier signal: θ=0∘ for binary 1 and θ=180∘ for binary 0.

**QPSK**

Quadrature Phase Shift Keying (QPSK) is a form of Phase Shift Keying in which two bits are modulated at once, selecting one of four possible carrier phase shifts (0, 90, 180, or 270 degrees). QPSK allows the signal to carry twice as much information as ordinary PSK using the same bandwidth.

**FSK**

FSK is a frequency modulation scheme in which digital information is transmitted through discrete frequency changes of a carrier signal.The technology is used for communication systems such as telemetry.

**QAM**

QAM is a signal in which two carriers shifted in phase by 90 degrees (i.e. sine and cosine) are modulated and combined. As a result of their 90° phase difference they are in quadrature and this gives rise to the name. Often one signal is called the In-phase or “I” signal, and the other is the quadrature or “Q” signal.

## AWGN Block sittings
* Initial speed: 67.
* Eb/No(dB) -10 or 10.
* Number of bits per symbol: 1.
* Symbol period(s): 1.
## Modulation Schemes
### BPSK [Binary Phase Shift Keying]:
**Paramerters**
* Random Generator set size = 2.
* Phase offset(rad) = 0.

**Block Diagram**

![Diagram](https://github.com/Hassanosama/Digital_Communication_Project/blob/master/BPSK/Figures/Diagram.png)

**Modulator [Before Noise]**

![Diagram](https://github.com/Hassanosama/Digital_Communication_Project/blob/master/BPSK/Figures/Before%20Noise.png)

**Demodulator [After Noise at -10 dB]**

![Diagram](https://github.com/Hassanosama/Digital_Communication_Project/blob/master/BPSK/Figures/After%20Noise%20at%20-10%20dB.png)

**Demodulator [After Noise at +10 dB]**

![Diagram](https://github.com/Hassanosama/Digital_Communication_Project/blob/master/BPSK/Figures/After%20Noise%20at%20+10%20dB.png)

**BER Diagram**

![Diagram](https://github.com/Hassanosama/Digital_Communication_Project/blob/master/BPSK/Figures/BER.PNG)

### FSK [Frequency-shift keying]:
**Paramerters**
* Random Generator set size = 8.
* M-ary number = 8
* Frequency separation = 6
* Samples per symbol = 17

**Block Diagram**

![Diagram](https://github.com/Hassanosama/Digital_Communication_Project/blob/master/FSK/Figures/Diagram.png)

**Modulator [Before Noise]**

![Before Noise](https://github.com/Hassanosama/Digital_Communication_Project/blob/master/FSK/Figures/Before%20Noise.png)

**Demodulator [After Noise at -10 dB]**

![After-10](https://github.com/Hassanosama/Digital_Communication_Project/blob/master/FSK/Figures/After%20Noise%20at%20-10%20dB.png)

**Demodulator [After Noise at +10 dB]**

![After-10](https://github.com/Hassanosama/Digital_Communication_Project/blob/master/FSK/Figures/After%20Noise%20at%20+10%20dB.png)

**BER Diagram**

![Diagram](https://github.com/Hassanosama/Digital_Communication_Project/blob/master/FSK/Figures/BER.PNG)

### QAM [Quadrature amplitude modulation]:
**Paramerters**
* Random Integer Generator Set size = 16, 64
* M-ary number = 16, 64
* Normalization method = Average Power
* Phase offset (rad) = 0

### QAM 16

**Block Diagram**

![Diagram](https://github.com/Hassanosama/Digital_Communication_Project/blob/master/QAM%20(16)/Figures/Diagram.png)

**Modulator [Before Noise]**

![Before Noise](https://github.com/Hassanosama/Digital_Communication_Project/blob/master/QAM%20(16)/Figures/Before%20Noise.png)

**Demodulator [After Noise at -10 dB]**

![After-10](https://github.com/Hassanosama/Digital_Communication_Project/blob/master/QAM%20(16)/Figures/After%20Noise%20at%20-10%20dB.png)

**Demodulator [After Noise at +10 dB]**

![After-10](https://github.com/Hassanosama/Digital_Communication_Project/blob/master/QAM%20(16)/Figures/After%20Noise%20at%20+10%20dB.png)

**BER Diagram**

![Diagram](https://github.com/Hassanosama/Digital_Communication_Project/blob/master/QAM%20(16)/Figures/BER.PNG)

### QAM 64

**Block Diagram**

![Diagram](https://github.com/Hassanosama/Digital_Communication_Project/blob/master/QAM%20(64)/Figures/Diagram.png)

**Modulator [Before Noise]**

![Before Noise](https://github.com/Hassanosama/Digital_Communication_Project/blob/master/QAM%20(64)/Figures/Before%20Noise.png)

**Demodulator [After Noise at -10 dB]**

![After-10](https://github.com/Hassanosama/Digital_Communication_Project/blob/master/QAM%20(64)/Figures/After%20Noise%20at%20-10%20dB.png)

**Demodulator [After Noise at +10 dB]**

![After-10](https://github.com/Hassanosama/Digital_Communication_Project/blob/master/QAM%20(64)/Figures/After%20Noise%20at%20+10%20dB.png)

**BER Diagram**

![Diagram](https://github.com/Hassanosama/Digital_Communication_Project/blob/master/QAM%20(64)/Figures/BER.PNG)

### QPSK [Quadrature Phase Shift Keying]:
**Paramerters**
* Random Integer Generator Set size = 4
* Phase offset (rad) = pi/4

**Block Diagram**

![Diagram](https://github.com/Hassanosama/Digital_Communication_Project/blob/master/QPSK/Figures/Diagram.png)

**Modulator [Before Noise]**

![Before Noise](https://github.com/Hassanosama/Digital_Communication_Project/blob/master/QPSK/Figures/Before%20Noise.png)

**Demodulator [After Noise at -10 dB]**

![After-10](https://github.com/Hassanosama/Digital_Communication_Project/blob/master/QPSK/Figures/After%20Noise%20at%20-10%20dB.png)

**Demodulator [After Noise at +10 dB]**

![After-10](https://github.com/Hassanosama/Digital_Communication_Project/blob/master/QPSK/Figures/After%20Noise%20at%20+10%20dB.png)

**BER Diagram**

![After-10](https://github.com/Hassanosama/Digital_Communication_Project/blob/master/QPSK/Figures/BER.PNG)






