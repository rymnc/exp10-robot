# exp10-robot
---
## Notes
  - This package was made as an addition to the batch 1's miniproject.
  - It is a simple four wheeled bot created using xacros + ros + gazebo.
---
## Setup Instructions
  - Launch the bot in gazebo: `roslaunch exp10-robot gazebo.launch` 
  - If you wish to change bot parameters head over to urdf/bot.xacro
---
## Footnotes
  - Over the course of the miniproject, I was able to get familiar with the ros development lifecycle, as well as usage of xacros in ROS, and how it is advantageous over writing plain URDF files. Writing URDF files by hand is very cumbersome. 
  - It is not extendable and reusable in this way.
  - Xacros simplify the development of any bot, as once the parameters are mapped mathematically, we can alter them to get models of different shapes and sizes, all while maintaining the same scale between links/joints.
---
