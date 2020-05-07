__Project 2: Hexapod__

__Problem statement:__
To develop a visual representation of a 18 DOF hexapod on a computer screen using the data obtained from the sensors attached on it.

__Design:__
In order to create a visual representation of the bot on a computer screen, we need some modelling software like AutoCAD or Fusion 360. This computer model should have 18 different-yet-connected parts that together make the Hexapod. Each part must be attached to a 6DOF IMU sensor in the physical model. Using some softwre, the computer generated 3D model must be programmed exactly to mimic the motion of the physical model. For this purpose, the data obtained from the IMU sensors must be integrated via a microcontroller and must sent to the computer using a serial port or even by wireless technology. This is the basic idea. The pipeline is:

Data from IMU sensors => Microcontroller => Computer's microprocessor => 3D model moving according to the data acquired and the code programmed into it


