# Diff_Drive_URDF

URDF Differential drive with one single caster ball.


effort_controllers/joint_velocity_controller 
    will adjust effort (force), using a PID controller, applied to a joint(s) in order to reach a desired velocity. 


velocity_controllers/joint_velocity_controllers 
    will pass the commanded joint velocity to the joint. The choice of controller depended on your robot.


