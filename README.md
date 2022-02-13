# TXD_CutOff_SDR
A FET/Relay based RF/TXD cutoff switch to protect SDR receivers which share the same antenna with a transceiver.
Input signal from the transceiver, in this case a Yaesu FT-991A is taken from the SQL pin on the Data port miniDIN 6 pins socket, as it's on a HIGH 5V level during RX and LOW 0V on TX.
The relay is constantly energised with the HIGH signal and will disconnect the SDR under a LOW signal.

Partlist

Assembly variant: 

Part     Value          Device          Package              Library      Sheet

+DCIN-                  PINHD-1X2       1X02                 pinhead      1
C1       0.22uF         C-EU025-024X044 C025-024X044         rcl          1
C2       0.10uF         C-EU025-024X044 C025-024X044         rcl          1
D1       1N4004         1N4004          DO41-10              diode        1
D2                      LED3MM          LED_3MM              SparkFun-LED 1
IC1      7805T          7805T           TO220H               linear       1
K1       HY1Z-5V        HY1Z-5V         HY                   relay        1
OK1      PC814          PC814           DIL04                optocoupler  1
R1       100K           R-EU_0204/5     0204/5               rcl          1
R2       1K             R-EU_0204/5     0204/5               rcl          1
R3       1K             R-EU_0204/5     0204/5               rcl          1
R4       1K             R-EU_0204/5     0204/5               rcl          1
RFGND1   MCS08          MCS08           MCS08                solpad       1
RFGND2   MCS08          MCS08           MCS08                solpad       1
RFIN                    2,54/0,8        2,54/0,8             wirepad      1
RFOUT                   2,54/0,8        2,54/0,8             wirepad      1
SQLTRIG                 PINHD-1X2       1X02                 pinhead      1
T1       RFD14N05L      RFD14N05L       TO229P250X658X985-3P RFD14N05L    1
