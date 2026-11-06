# ParkingSystem

INTRODUCTION 

In urban areas, due to heavy traffic, finding a proper parking space becomes a huge 
hindrance for drivers especially when they’re in a hurry. A multislot parking system is 
one such innovative design that provides drivers ample amount of parking space and 
saves them a lot of time. 
A multislot parking system would involve the necessary hardware such as sensors as 
well as the software that would require to run the system. In our project, we have 
designed the system by only using the features present in the LabVIEW software. 

FRONT PANEL

The front panel consists of light indicators and six slots, each containing the time 
occupied by the vehicle and the cost of occupancy. On the left side of the front panel, 
we have added a strip of LED indicators that would display the vacancy of the slots. 
This can be viewed by the driver at the entrance of the parking lot. A button is added 
which would mimic the entry of the car into the parking lot. We have created 6 
different cases in which different slots would be occupied at different times. The time 
and cost would be displayed accordingly using the formula we have generated in the 
block diagram. 

BLOCK DIAGRAM 

We have four different types of indicators and each of them are required for six slots. 
Therefore, we have declared local variables for all these 24 indicators. As mentioned 
earlier, we have pre-defined six different cases. Each of these cases are given as 
frames in the framed sequence structure. This is then placed inside a case structure 
where the car entry button is given as the case selector. 
The local variables for the LED indicators are placed inside each of these frames and a 
true constant or a false constant is given to them based on our cases. To calculate the 
time, a random number generator is added to each frame that would generate different 
timings every time the program is run. It is then divided by 1000 to get the time in 
seconds. We have kept the cost as 5Rs per second. The local variables for time and 
cost are placed within this case structure accordingly. The entire case structure is 
placed inside a While Loop where the loop condition is given to the car entry button.  


CONCLUSION 

The LabVIEW software is very useful to design a 
multislot as well as a multilevel parking system as it 
allows the designer to run simulations and test the system 
in an effective way. Furthermore, this system will benefit 
a large number of people in urban areas who face 
difficulties parking their vehicles due to space constraint. 
