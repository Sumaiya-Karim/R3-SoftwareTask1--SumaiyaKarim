
# Approach: 
Step 1: Studied the Arduino UNO I/O pins 
Step 2: 7 segment decoder CD4511
Step 3: Created a small circuit just to test the potentiometer. I was able to obtain a expected output from potentiometer.
Step 4: Tried to use the 7 segment and display the output.However, realized that Arduino did not have enough pins for two 7 segment circuit connections) the 7 segment decoder (CD4511)  
Step 5: looked up BCD (Binary Coded Decimal)

A BCD to 7 Segment Decoder will require only 4 Arduino Pinouts and two of them will use only 8 Digital Pinouts. This is better than using two 7 segment with arduino due to limited number of pins on arduino. 

BCD to Decimal Mapping is as follows.

BCD ---- DECIMAL

0000 ---- 0

0001 ---- 1

0010 ---- 2

0011 ---- 3

0100 ---- 4

0101 ---- 5

0110 ---- 6

0111 ---- 7

1000 ---- 8

1001 ---- 9

The BCD to Decimal Conversion can go upto 15 but we can only display until  9  on a single 7 - Segment Display
Step 5: Test one 7 segment with 7 segment decoder and was able to make it work 
step 6: Added the next 7 segment with second deocder and tested out the code given in the following website https://www.instructables.com/Two-Digit-TimerCounter-Using-Arduino-7-Segment-Dis/ for each step 
Link to TinkerCad: https://www.tinkercad.com/things/0Bv2I1a1E1U
# Challenges I encountered  & What I learned 
This is my first time using GIT Terminal commands so it took me while to get used to with terminal commands. Due to time time constraint, I wasn't able sucessfully complete the project but I learned how to use the terminal commands and how to create neat circuit diagrams on tinkerCAD and arduino simulation features on TinkerCAD
