vrep-ubuntu
===========

Launch the V-REP robot simulator from a docked icon on Ubuntu

I love using the V-REP simulator from Coppelia Robotics, but in Linux they tell you launch it from the directory in which it was installed.  As shown in this video, I figured out a workouround:

1) Download / clone from github: https://github.com/simondlevy/vrep-ubuntu/

2) cd vrep-ubuntu (or vrep-ubuntu-master)

3) Edit (I use vi) vrep.sh and vrep.dekstop,changing for your own directory structure

4) mv vrep.sh $HOME/Software (or whever you specified in vrep.desktop)

5) mv vrep.desktop ~/.local/share/applications

6) mv vrep.png ~/.local/share/icons

7) Click on the Unity launcher (swirly Ubuntu icon in upper-left of your screen),  type V-REP, and drag the icon into the launcher
