# Chapter9 FAQ

## 4.1 Image transmission picture freeze, delay

Right-click to close the image transmission, and then reopen the image transmission, if the problem still exists, please wait for the robot to drive away from this signal blocking area before trying again.

## 4.2 The visual status shows "missing" during the construction process, and no cyan feature points appear in the black and white image transmission screen

There are two cases as follows:
   
a. After turning on the vision, the visual state has not been "tracking";
   
b. "Tracking" appeared before the visual state, and suddenly became "lost" during the remote-control drawing process.
  
SOLUTION: 
   
a. Try to ensure that the robot moves in a straight line, move forward for a period of time and then back for a period of time, and repeat the action until the visual state becomes "tracking";
   
b. Return the robot (ensure that the orientation of the robot remains unchanged) to the closest position where the visual state is "tracking", so that the robot vision system is locked again;
   
c. After trying both methods for many times, if it still shows "missing", please turn off the vision and then turn on the vision again, and scan the image from the beginning.

## 4.3 After starting the service, the visual status always shows "lost" and the robot swings in place

This situation indicates that the robot cannot recognize the current position, and there are two possibilities:
  
a. The current position has not been recorded during the construction scan, please remote control the robot to the scanned position to ensure that the orientation of the robot is the same as the orientation during the construction, and then restart the autonomous inspection;
  
b. The light intensity or item distribution at the current location has changed significantly, and the environment needs to be rescanned for construction, and the inspection paths and stations also need to be redrawn.

## 4.4 Unable to turn off navigation service

a.It may be that the network connection is not available, you can try to make the control terminal close to the robot, and then turn off the navigation service;

b. The system processing information has not yet reacted, just a moment later;

c. When it is found that it still cannot be turned off normally, you can manually turn off the robot power switch.

## 4.5 When planning the path, the loaded map shows a mess of gray dots, and the blue trajectory point of the robot is not like the remote control path when the map is scanned. 

This means that the creation of this map has failed. Please rescan the map and try again.

## 4.6 The client cannot connect to the robot

Please check your network to make sure that both computer and robot already connect to the network.
