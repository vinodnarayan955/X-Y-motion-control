# X-Y-motion-control
LabVIEW code for X-Y motion control

**Prerequisite:**
1. At a minimum LabVIEW run time enviornment setup (with the JKI package add-on) on a 64-bit windows OS system (LV 2018 or above)
2. Install LV 2018 (32-bit) or above on a 64 bit windows OS system
3. Install VI Package Manager (VIPM) by JKI, download and install JKI SM as an add-on

**Launch Instructions**
1. Download X-Y-motion-control project which contains all the source code and the executable
2. Go to builds-----> X-Y motion control----> X-Y motion control app----> and then double-click on X-Y stage sim app.exe to launch the simulator app

**Following are the instructions to use the simulator app for X-Y motion control**
1. User can change home position once for both X and Y (initially) before stepping through different steps
2. Set position between 0 to 200 (The system is capable of generating finest resolution positions as needed by the user)
3. Hit Move to see the dial move to a desired set position as set from above step
4. Hit return home (X or Y) to return to set home position
5. 2 separate dials to exercise X and Y motion axes are designed to give user better control

**Current Assumptions:**
1. Since it is a simulator app, the goal has been to mimic the system as much as possible with the set of minimum requirements that were given. 
2. Parameters such as speed, are not taken into consideration as input parameters, idea was to create a very simple app to demonstrate the X-Y control in the most ideal way and without further requirements and hardware it was not worth thinking about the use cases and parameters related to same. 
3. The max range is assumed to be 200 as a spec for step range that X-Y axes can move as an example for this simulator application
4. 1:1 relationship between the movement and the number of steps set
