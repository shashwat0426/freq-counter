# freq-counter

# Introduction-
This device measures the low frequency signal of sinusoidal wave having frequency in integers.

# Apparatus used-
1. 7-Segment Display Common Cathode -RED
2. IC CD4033 
3. OpAmp UA709
4. Resistors and Capacitors
5. Batteries
6. Proteus 8 Professional

# Working Principle-
. This circuit is based on the simple definition of frequency, which is the number of cycles per second. Basically, a Square Wave
Generator circuit (here we used schimdt trigger by using UA709) is used to produce a simple pulse wave. This pulse is given as clock[PIN 1]
to CD4033 Counter.
As we are measuring frequency so it is required that counting will be done for only 1 sec. So we input single pulse to clock inhinit [PIN 2].
 So that untill the pulse is low, counter counts and as it will go high, the counting will stop. Since pulse is of duration 1 sec 
 we will get the frequency of our input sinusoidal wave .
 
 ![image](https://user-images.githubusercontent.com/60343675/132389479-55ff7865-26d0-435d-8aea-71058590be51.png)



![image](https://user-images.githubusercontent.com/60343675/132389546-b3c457ea-173a-4da3-a46b-18f081216c8b.png)

