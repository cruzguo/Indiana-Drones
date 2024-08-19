**Part A: SLAM**
Implement a SLAM module to estimate the positions of trees and the drone itself using given movements and measurements.

**Function:** process_measurements(measurements: Dict) updates the drone's and trees' positions based on sensor data.
**Function:** process_movement(distance: float, steering: float) updates the drone's position based on movement commands.
**Function:** get_coordinates() retrieves the estimated locations of the drone and trees.
**Part B:** Navigation
Develop an action planner to navigate the drone to a treasure while avoiding obstacles.

**Function:** next_move(measurements: Dict, treasure_location: Dict) determines the next action for the drone, either to move or extract the treasure.
**Setup**
Clone the repository.
Implement the SLAM and navigation classes in indiana_drones.py.
Test using the provided testing_suite_indiana_drones.py.
Visualize results with visualize.py.
