# my_stdr_control
An minimal, example node to illustrate control of the STDR mobile robot with open-loop commands. Extended to demonstrate how a robot might have a chance of navigating to the top-left-corner of STDR Simulator's map.

## Example usage
`roslaunch stdr_launchers server_with_map_and_gui_plus_robot.launch`
to start the simulator.  Run a simple, open-loop command sequence with:
`rosrun my_stdr_control my_stdr_open_loop_commander`

    
