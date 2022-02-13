# TXD_CutOff_SDR
A FET/Relay based RF/TXD cutoff switch to protect SDR receivers which share the same antenna with a transceiver.
Input signal from the transceiver, in this case a Yaesu FT-991A is taken from the Data port miniDIN 6 pins socket, as it's on a HIGH 5V level during RX and LOW 0V on TX.
The relay is constantly energised with the HIGH signal and will disconnect the SDR under a LOW signal.
