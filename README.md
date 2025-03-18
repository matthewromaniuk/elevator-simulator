# C++ Elevator Simulator

## How to Run
To run elevator simulator use the ElevatorSim Application or run ElevatorSim.cpp

## Process
Will ask for two parameters before beginning simulator:
* Scale
* Capacity

Move the command prompt to the side of the screen so you can see both the canvas and command prompt.

Building of simulator takes about 30 seconds.

To use simulator, click call buttons on right side of screen, this will spawn a waiting passenger.
After the elevator reaches the elevator, it requires a floor request, to do this, click the panel of numbers in the bottom left.
A list of keyboard inputs will appear on the command prompt,  these allow you to stop, continue, reset, and end the simulator.

**CANVAS MUST BE CLICKED ON FOR BOTH KEYBOARD AND MOUSE INPUTS TO WORK**

## Important Notes
Some click requests (if elevator is in motion) may take multiple rapid clicks, it will occasionally stop when trying to add passenger, just click again and it will work. getAsyncKeyState should prevent this from happening but does not.
To add a waiting passenger while the elevator is moving, it seems that you need to double click a couple times, then when the elevator stops click again. 

The elevator panel is off when the elevator is empty and when in motion.
