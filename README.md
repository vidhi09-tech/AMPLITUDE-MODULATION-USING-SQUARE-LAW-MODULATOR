# AMPLITUDE-MODULATION-USING-SQUARE-LAW-MODULATOR
Generation of an AM signal by a square law modulator and verifying the signal power of a received signal, which has undergone with amplitude modulation at the transmitter and mixed with an AWGN of zero mean and 0.2 variance during transmission.

This code is divided into 4 sub parts:
•	Generate message and carrier signal

•	Amplitude modulation using carrier square law demodulator

•	Noise addition

•	Demodulation of the transmitted signal

![image](https://user-images.githubusercontent.com/63573906/113031692-a2ffaf00-91ac-11eb-8323-7874e38a7789.png)

The MATLAB output results are mentioned below:

 
![image](https://user-images.githubusercontent.com/63573906/113031947-ea863b00-91ac-11eb-8da7-004ca7ed26af.png)

Figure 1: baseband signal and carrier signal

 
![image](https://user-images.githubusercontent.com/63573906/113031972-f114b280-91ac-11eb-9e2f-98ca197a3489.png)

Figure 2: output of adder and nonlinear device

 
![image](https://user-images.githubusercontent.com/63573906/113031995-f7a32a00-91ac-11eb-96b7-00bba048bb56.png)

Figure 3: AM modulated signal

 ![image](https://user-images.githubusercontent.com/63573906/113032019-feca3800-91ac-11eb-9d0c-7a5bd4dd44e9.png)

Figure 4: AWGN noise is added to AM signal

 ![image](https://user-images.githubusercontent.com/63573906/113032043-05f14600-91ad-11eb-98d1-f185f3bc8590.png)

Figure 5: demodulation of AM signal (without noise) &
 demodulation of corrupted AM signal (with AWGN)

 ![image](https://user-images.githubusercontent.com/63573906/113032056-0ab5fa00-91ad-11eb-90ac-c584d45933d0.png)

Figure 6: spectrum of AM signal &
Spectrum do demodulated corrupted signal (with AWGN)

 
![image](https://user-images.githubusercontent.com/63573906/113032073-10abdb00-91ad-11eb-9229-31b2faf3f345.png)

Figure 7: command window output 
