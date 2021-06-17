# X-Y-motion-control
LabVIEW code for X-Y motion control

**Following are the instructions to use the simulator app for X-Y motion control**
User can change home position once for both X and Y (initially) before stepping through different steps
Set position between 0 to 200 (The system is capable of generating finest resolution steps as needed by the user)
Hit Move to see the dial move to a desired set position from point 6
Hit return home (X or Y) to return to set home position

**Current Assumptions:**
Since it is a simulator app, the goal has been to mimic the system as much as possible with the set of minimum requirements that were given. 
Parameters such as speed are not taken into consideration as input parameters, idea was to create a very simple app to demonstrate the X-Y control in the most ideal way and without further requirements and hardware it was not worth thinking about the use cases and parameters related to same. 
THe max range is assumed to be 200 as an example for this simulator application

**Prerequisite:**
At a minimum LabVIEW run time enviornment setup on a 64-bit windows OS system (LV 2018 or above)
