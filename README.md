# grbl-IO
grbl-IO is a collection of hardware and software for the external control of grbl-compatible controllers.  
The well-structured building blocks can then be used flexibly to control or operate different machines.  
It should be suitable for CNC, 3D printing, laser cutting and other applications  
The current efforts are to create various extensions for the operation of FluidNC http://wiki.fluidnc.com/

# Hardware designs
Several designs are being considered to operate the various machines and applications.  
Whether simple and cheap, or complex and expensive, the core is always grbl-IO  
At the moment we are working on several designs that are presented here to build or buy.  

# Software designs
The software is divided into blocks for flexible use.  
base / read / send / in / out / ui  
Each block consists of at least the following units:
variables / base / config / handler

# first function in separate repo  
https://github.com/PatrikRindlisbacher/grbl-Status-light-tower-M5-Atom-Matrix
!!!! The Light Tower is already supported by 3 boards.
# grbl  
It should support GRBL from the current version 1.1  
https://github.com/gnea/grbl/wiki/Grbl-v1.1-Interface

# base function  
![image](https://user-images.githubusercontent.com/39780457/224492057-5cd22552-cdc0-4af9-aa42-ebd92e5011fe.png)

# Hard and software
In order to be able to advance the work quickly,  
we have made a preliminary selection of hardware and software that we support.

# Related projects from other users
https://github.com/grblHAL/grblHAL_MessageParser 
https://github.com/AC8L/FluidNC-Pendant  
https://github.com/gjkrediet/Fluid-controller  
https://github.com/quezadaminter/GrblJogCtrl  
http://dangeroustools.com/2020/01/03/dro-and-jog-wheel-for-grbl/  
https://openbuilds.com/builds/interface-cnc-touch-control-system.9688/  
