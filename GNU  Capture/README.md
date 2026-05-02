**README for LESSON8.grc**
Note: lab3.grc is from an old attempt that was abandonded from the lab

Lesson 8 consists of three main blocks: 
- osmocom source
- QT GUI Frequency Sink
- QT GUI Time Sink

The remaining tertiary blocks are:
- complex to mag 
- QT GUI Range
- variable


The osmocom source connects to the HackRF and outputs data that the HackRF receives. 
The frequency sink shows the frequncy contents over a range from 290MHz to 400MHz. 
The expected frequency of the signal from the garage opener is 300MHz.
The time sink shows the digital message content of the signal. It is important to make sure 
that the time resolution isn't too zoomed in for a legible reading of the binary message. 
