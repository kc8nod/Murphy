# Murphy
An example project for the FIRST Robotics Competition.

This project runs on the RoboRio controller which is purpose-build for the First Robotics Competition.

## Setting up tools

Getting started with Java and the FRC environment: https://wpilib.screenstepslive.com/s/4485/m/13809

To develop on a Mac, you only need Eclipse and the FRC plugins.
When asked, set the team number to **1520**

Clone this project into your Eclipse workspace directory,
then File -> Import and select ```Existing Project into Workspace```

## Downloading code

Deploying code from a Mac can only be done over ethernet/wifi. USB will not work. You can make sure Murphy is connected to the network by:
```
$ ping roboRIO-4680-FRC.local
PING roborio-4680-frc.local (10.251.0.220): 56 data bytes
64 bytes from 10.251.0.220: icmp_seq=0 ttl=64 time=28.216 ms
```

From Eclipse, select your project and choose: **Run -> Run As -> WPILib Java Deploy**
Some errors are normal, but you must see ```BUILD SUCCESSFUL```