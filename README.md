# The RCML Community rules
---

## What is RCML?
RCML is acronym of The Robot Control Meta Library. Old name is The Robot Control Meta Language.
It is programming toolkit for robotics, which was focus at industrial robotics and mobile industrial robotics. Now it open for all robotics.

The RCML approach is independence of program apps for robotics, from composition of robot hardware & software.

One boring example from industrial robotics: *if your app need only moving work tool only in XYZ coordinates, then you use 4-axis robot class (4 axis is enough to XYZ movements) in code of your app. Moreover, you should not care about which brand of robot, which will work with your app. In addition, you should not care about how many axes it have, because 5- and 6-axis robots also can execute XYZ movements. The RCML verify, that robot is compatibility with your app. In addition, it do not allow your app work with wrong robot which is incompatible you app.*

Therefore, we believe that this approach can create new era and new market in programming sphere.
**Era of robotics programmers, new market of robotics software**, when any programmer can create app for any robot.
Like now, when any programmer can create mobile app and do not care about which is CPU, motherboard, or RAM within every device.

Again, **this talk not about hardware compatibility, it about functional compatibility by programming tools**.
It is mission of the RCML.

## What is goal of the RCML community?

First and main objective of RCML is creating unified SDK and toolkits for robotics programming for increasing and growth of environment of app developers and robot developers.

This SDK should be like glue for different robots, tools, sensors, programming utilities and libraries, etc.
This seems like ROS approach, but unlike it, The RCML follow the production way by classification, unified and standardization API of different units of robotics apps.

## How to be involved to the RCML project?
You may be involved by different way. The simplest way is contribute to RCML code at any project, tool or SDK unit.
Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us.
Also you can just populization the RCML approach and ideas in world.

## Relevant docs
This file contains information about basic goals and principles for whole The RCML Community.
It is default for most projects of community. The specific projects rules are described within each repository of RCML (rcml-tech organization).

## License
All open source RCML code distribute by MIT license by default, see LICENCE file.
In any way, each RCML repository of code contains LICENSE file that notice about license to code within that repository.
