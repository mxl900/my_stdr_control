# my_stdr_control

Control scripts for STDR mobile robot with open-loop commands. Running the scipt will move the tutlebot from its initial postion to the upper left corner on the map.

## Example usage

`roslaunch stdr_launchers server_with_map_and_gui_plus_robot.launch`
to start the simulator.  Run a simple, open-loop command sequence with:
`rosrun my_stdr_control stdr_open_loop_commander`

## Running tests/demos
    
