# ROS2 Study (Jazzy)

Personal notes and practice while learning ROS2.

## Environment
- Ubuntu 24.04 (WSL2)
- ROS2 Jazzy Jalisco
- Python 3

## Notes
- Installed ROS2 Jazzy and set up the workspace
- Ran `turtlesim` and verified basic ROS2 execution
- Controlled the turtle using `turtle_teleop_key`
- Observed velocity and pose topics:
  - `/turtle1/cmd_vel`
  - `/turtle1/pose`
- Visualized node-topic relationships using `rqt_graph`

## Practice
- Implemented a simple ROS2 Python node
- Published velocity commands to `/turtle1/cmd_vel`
- Generated circular motion using linear and angular velocity

## Next
- Modify velocity parameters (circle size, stop conditions)
- Subscribe to `/turtle1/pose`
- Move the turtle to a target position
