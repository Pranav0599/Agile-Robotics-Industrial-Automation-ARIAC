# Agile-Robotics-Industrial-Automation-ARIAC-

To install the ARIAC workspace, please refer to the instructions in this link: https://github.com/usnistgov/ARIAC/blob/ariac2022/wiki/tutorials/installation.md.

Once the installation is complete, follow the below steps to run the code:

1. Build the package by extracting it and pasting the "group2_rwa4" folder in the "src" directory of the "ariac_ws" folder.
2. Run "catkin clean -y && catkin build" in the terminal.
3. Use "source devel/setup.bash" to set up the environment.
4. Run the package using the command "roslaunch group2_rwa4 ariac.launch".
The package should not throw any error as long as the real-time factor (RTF) is below 0.8. If the RTF is below 0.8, adjust the step size in the "nist_gear/worlds/ariac.template" file.
