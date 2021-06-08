# Project1
This project creates an environment ("world") for simlution in Gazebo. The environment includes an enclosed space ("building") and robots. The building is arbitrary but so designed that small robots can freely travel through it. The environment's size allows a complete view of the space and robots in it from an overhead vantage point. Objects were included in the space to present both path planning and obstacle avoidacne challenges while also providing features for localization. 

The screen shot below show the simulation environment as rendered in Gazebo:

![Simulation environment](</pngs.d/Project1World.png>)

There is an enclosed space around which robots can travel in a nominal loop. For laughs & giggles and to put some permanent obstacles in the robot's path a water fountain and a fire hydrant were placed at the lower corners. The top part of the loop has a row of posts that eliminate a simple straight go-araound path if there are obstacles on the nominal path. Each interior space has two doors allowing a path into and out of the enclosed space.

Two robots were modeled. These are simple but typical delivery type robots. The first is the trailing ball bot created in the Gazebo tutorial on robot modeling:

![Rollerball bot](</pngs.d/Ballbot.png>=300x)

