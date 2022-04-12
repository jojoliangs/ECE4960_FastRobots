layout: page
title: "Lab 8"
permalink: /ECE4960_FastRobots/lab8/

# Lab 8 - Stunt
I chose to perform Task B, where my robot drives toward the wall at max speed then turn around once close enough to the wall. Here is a video demo

<a href="http://www.youtube.com/watch?feature=player_embedded&v=mpxP_u9JrW8" target="_blank"><img src="assets/img/lab8/demo_thumbnail.PNG" alt="" width="240" height="180" border="10" /></a> 

One challenge that I ran into included being able to get my robot to drive quickly after a setpoint change. As you can see in this blooper, my robot consistently does the waggle dance. I discovered that this problem was exacerbated as my battery level dropped. The two motors did not turn at the same rate when the current supplied was lower, which caused the robot to bias toward one way or the other and requiring the PID controller to take over and decrease the robot's speed. I was able to mitigate this issue by increasing the acceptable error and taking a dinner break while charging my battery. 

<a href="http://www.youtube.com/watch?feature=player_embedded&v=AcGpLod92HQ" target="_blank"><img src="assets/img/lab8/waggleBlooper_thumbnail.PNG" alt="" width="240" height="180" border="10" /></a>

Another challenge that I encountered was the lighting in the Phillips hallway. The corner where the tape lines were setup is directly under one of the only lights that were on in that hallway. As a result, my robot would start in a darkened section of the hallway and point into a light section of the hallway. For some reason, this interfered greatly with the TOF sensors.The robot would register a wall when there is just a lighting inconsistency. This phenomenon occured as well when I tried starting the robot in a lit section of the hallway driving toward a dark section. As a result, I chose to move to the other end of the hallway where the lighting was even. 

